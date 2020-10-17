# GDG DevFest 2020

Assalamualaikum and Hello!

Here you can find instructions on how to make the necessary preparation for the "Build and Deploy Machine Learning Model" talk if you wish to follow along during the session.

## Preparing your environment

Before you start to write codes, it is often necessary to prepare your machine in order to be able to write and run your codes. If you are not sure what that means, don't fret!. The steps are explained below.

There are three toolkits that will be used during this session i.e. Anaconda, Docker and GCP SDK (optional).

### First Toolkit: Anaconda (or Miniconda)

To install the have two options. You only have to either pick one.

#### Option 1: Installing Anaconda

If you are new to programming and is unfamiliar on how to set up your development environment, then the easiest way is to start by installing Anaconda from [here](https://www.anaconda.com/products/individual). This route is the easiest for absolute beginners.

#### Option 2: Installing Miniconda

While Anaconda is the easiest, the installation file size is rather large. This is because Anaconda tries to include all the important tools in the field of data science. More often than not, you do not need the full suite. Hence, Miniconda. 

Miniconda allows you to have a minimalist set of tools, just enough to get you started and you can build upon it as you progress further.

You may find the installers [here](https://docs.conda.io/en/latest/miniconda.html).

Note: Grab the one with Python 3.8.

#### Create your environment

Once you're done with that, it is time to create your environment. This basically means installing the necessary libraries that will help you in creating your machine learning model and the API. 

- While inside your terminal, go ahead and clone this git repo.

`git clone https://github.com/ahmadmusaddiq/gdg-devfest-2020-demo`

- Then navigate to the repo.

`cd gdg-devfest-2020-demo`

- Run the following command.

`conda env create -f environment.yml`

Should you encounter issues during this step, feel free to contact any of the volunteers or the organisers.

### 3) Second Toolkit: Docker Desktop

Docker is primarily used to containerise your application.

Go ahead and grab the installer from [here](https://www.docker.com/products/docker-desktop).

### 4) [OPTIONAL] Third Toolkit: GCP SDK

Once we're done with the containerisation, we will deploy it to GCP.

WARNING: Deploying to GCP will incure charges. Only proceed if you understand the implications of following these steps.

- Start by getting the GCP SDK. Follow the instructions listed [here](https://cloud.google.com/sdk/docs/install)

- You will need to create your Project. Instructions can be found [here](https://cloud.google.com/resource-manager/docs/creating-managing-projects).

- You will also need to attach a billing account.

## Getting the dataset

The dataset we will be exploring in the session will be from Data.gov.bn.

You can grab the dataset [here](https://www.data.gov.bn/Lists/dataset/mdisplay.aspx?ID=777).