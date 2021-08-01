# MSc_Thesis_Abstractive_Summarization
Repository of the different models used for my dissertation and the web application
ohmeow-blurr == 0.0.32 

gcloud builds submit --tag gcr.io/text-summarizer-321212/streamlit-summarizer --project=text-summarizer-321212


gcloud run deploy --image gcr.io/text-summarizer-321212/<streamlit-summarizer> --platform managed --project=text-summarizer-321212 --allow-unauthenticated