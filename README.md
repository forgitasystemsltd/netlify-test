# Kova Order API — CORS Test

Static test page deployed to Netlify to verify cross-origin requests to `https://kova.ng/api/order`.

## Deploy to Netlify

1. Push this folder to a new GitHub repo
2. Connect the repo to Netlify
3. Or use Netlify Drop: drag this folder onto https://app.netlify.com/drop

## Test

Open the deployed URL in a browser and submit the form. It should return `{"success":true,"message":"Order received"}` without CORS errors.
