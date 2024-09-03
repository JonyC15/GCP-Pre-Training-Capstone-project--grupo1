# GCP-Pre-Training-Capstone-project--grupo1

This project is about a website for European traveling, uploaded to a Cloud Run service to practice deploying in Google Cloud Platform.
In the Cloud Run we have the
Original HTML project which is from: https://github.com/GNiruthian/Europe-Travel-Website-html-css-js

The whole process started with us making a clone of that site provided so wecould have the different versions of it saved.
In this case at a repository that will allow us to modify many times being able to retrieve the previous version if the modifications 
are not at customer satisfaction.
We went for Cloud Run looking to get the best for ratio usage - cost.

The process as follows: After we cloned the repository we made the Docker Image and pushed to the Google Artifact Registry Service.
Using Cloud Run we deployed the Docker Image with a Load Balancer that will allow it be reached for the general public.


