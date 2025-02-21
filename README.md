# Rapyd API Request Signatures PHP Code Sample

When you send an HTTPS REST request to the Rapyd Payments platform, you must include specified header parameters, including a signature. These headers are required for both the production platform and the sandbox. The headers are not required in the response from your remote authorization server.

The signing process helps secure requests in the following ways:
- Verifies that the requester is an authorized user. 
- Protects data from tampering in transit. 
- Rejects requests from unauthorized persons. 

## What do you need to start
- Rapyd Account (https://dashboard.rapyd.net/sign-up).
- PHP 8.x and Composer.

## How to run a sample application
- Log in to your Rapyd account
- Make sure you are using the panel in "sandbox" mode (switch in the top right part of the panel)
- Go to the "Developers" tab. You will find your API keys there. Copy them to the .env file
- Open a terminal in the cloned directory and run `composer install`
- In the same terminal window, run `php -S localhost:8000`
- Turn on your browser and go to `http://localhost:8000`

## Get Support 
- https://community.rapyd.net 
- https://support.rapyd.net 
