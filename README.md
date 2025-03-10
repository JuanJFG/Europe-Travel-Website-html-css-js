# Europe Travel Website Project and Implementation with GCP


This project deploys a static website for Travel Europe LLC using various Google Cloud services. The original website repository can be found here: [https://github.com/GNiruthian/Europe-Travel-Website-html-css-js/](https://github.com/GNiruthian/Europe-Travel-Website-html-css-js/).


## Deployment Options


The website has been deployed on the following Google Cloud services:


-   **Google Kubernetes Engine (GKE):** [http://34.133.13.1/]
-   **Google Compute Engine (GCE):** [http://34.67.99.169/]
-   **Cloud Run:** [https://europe-travel-cloudrun2-774619059863.us-central1.run.app/]
-   **App Engine:** [https://guandique-dev.uc.r.appspot.com/]


## Project Scope


This project demonstrates deploying a static website using different Google Cloud services, showcasing scalability and management of containerized applications. The deployment includes setting up a load balancer with an external endpoint for global access when using GKE.


## Development Process


1.  Copied the original GitHub repository.
2.  Ran the webpage locally.
3.  Created a Docker container for the webpage.
4.  Submitted the container image to Artifact Registry.
5.  Deployed the webpage using GKE with an HTTP load balancer.
6.  Deployed the webpage using a GCE VM.
7.  Deployed the webpage using Cloud Run.
8.  Deployed the webpage using App Engine.

