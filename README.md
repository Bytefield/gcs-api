You can stream logs from the command line by running:
  $ gcloud app logs tail -s default

To view your application in the web browser run:
  $ gcloud app browse

# URL model
curl -m 70 -X POST https://us-central1-codebox-studio.cloudfunctions.net/myFunction \
-H "Authorization: bearer $(gcloud auth print-identity-token)" \
-H "Content-Type: application/json" \
-d '{}'