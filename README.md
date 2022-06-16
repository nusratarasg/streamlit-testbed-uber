gcloud builds submit --tag gcr.io/testbed-353021/Uber_Streamlit  --project=testbed-353021

gcloud run deploy --image gcr.io/testbed-353021/Uber_Streamlit --platform managed  --project=testbed-353021 --allow-unauthenticated