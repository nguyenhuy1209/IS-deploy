# Install requirements
`pip install -r requirements.txt`

# Download model from S3

`mkdir -p model/data/model_files && cd model/data/model_files && curl -O https://grammarly-nlp-data-public.s3.amazonaws.com/gector/xlnet_0_gector.th`