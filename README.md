build container image
gcloud builds submit --tag gcr.io/beginners-project-69/perform_ocr
gcloud builds submit --tag gcr.io/<idprojectgooglecloud>/<nama container image>

deploy container image to cloud run
gcloud run deploy --image gcr.io/beginners-project-69/perform_ocr --platform managed
gcloud run deploy --image gcr.io/<idprojectgooglecloud>/<nama container image> --platform managed


https://perform-ocr-wf2dwnbrwq-et.a.run.app/

endpoint
https://perform-ocr-wf2dwnbrwq-et.a.run.app/ocr

