# Installation Guide

## Prerequisites

Make sure you have Docker installed. Refer https://docs.docker.com/get-docker/ for more information.

## Setup

1. Open your terminal in the `PoC-super` directory. 
2. Enter `docker-compose build`.
3. Change directory (`cd`) to `./PoC-vote/vote_app` and enter `python manage.py migrate`.
4. Change directory back to `PoC-super` and run `docker-compose up`.
5. Done!