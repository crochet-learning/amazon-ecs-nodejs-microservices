## Notes:

`aws get-login` is depreciated. Instead, use `aws get-login-password`

    aws ecr get-login-password \
    --region us-east-2 \
    | docker login \
    --username AWS \
    --password-stdin 894947003762.dkr.ecr.us-east-2.amazonaws.com/api