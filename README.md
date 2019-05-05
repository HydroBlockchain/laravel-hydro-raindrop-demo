# Laravel Hydro Raindrop Demo

This is a Laravel application for demo purposes. 

With a few simple steps you should be up and running with having a Hydro Raindrop MFA integration.

## Requirements

Check the official [installation Laravel documentation](https://laravel.com/docs/5.8/installation):

## Getting started

1. Clone the repository:

```
git clone git@github.com:adrenth/laravel-hydro-raindrop-demo.git
```

2. Navigate to the project root and install the dependencies:

```
composer install
```

3. Register your application at [https://www.hydrogenplatform.com/sign-up]()

Run the command:

```
cp .env.example .env`
```

And enter the details in the `.env` file:

```
;
; Hydro Raindrop
;
HYDRO_RAINDROP_CLIENT_ID = "[Client ID here]"
HYDRO_RAINDROP_SECRET = "[Client Secret here]"
HYDRO_RAINDROP_APPLICATION_ID = "[Application ID here]"
HYDRO_RAINDROP_ENVIRONMENT = "sandbox"
```

4. Open your browser and navigate to `/register` and register for an account.

5. Login with your credentials and set up Hydro Raindrop with your personal HydroID. That's it!
