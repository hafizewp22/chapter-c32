# Start Program in terrminal:

go run main.go middleware.go

# Testing in terrminal (Otentikasi):

curl -X POST --user noval:kaliparejaya123 http://localhost:8080/login

# Testing in terrminal (Mengakses Endpoint):

curl -X GET \
    --header "Authorization: Bearer eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJleHAiOjE1Mzg2NTI0NzksImlzcyI6Ik15IFNpbXBsZSBKV1QgQXBwIiwiVXNlcm5hbWUiOiJub3ZhbCIsIkVtYWlsIjoidGVycGFsbXVyYWhAZ21haWwuY29tIiwiR3JvdXAiOiJhZG1pbiJ9.JREJgUAYs2R5zuquqyX8tk23QlajVVe19susm6JsZq8" \
    http://localhost:8080/index
