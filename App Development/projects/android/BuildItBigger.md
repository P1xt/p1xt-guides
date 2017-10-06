## Project Overview
In this project, you will create an app with multiple flavors that uses
multiple libraries and Google Cloud Endpoints. The finished app will consist of four modules:

1. A Java library that provides jokes
2. A Google Cloud Endpoints
(GCE) project that serves those jokes
3. An Android Library containing an
activity for displaying jokes 
4. An Android app that fetches jokes from the GCE module and passes them to the Android Library for display

## Why this Project?

As Android projects grow in complexity, it becomes necessary to customize the behavior of the Gradle build tool, allowing automation of repetitive tasks. Particularly, factoring functionality into libraries and creating product flavors allow for much bigger projects with minimal added complexity.

##What Will I Learn?

You will learn the role of Gradle in building Android Apps and how to use Gradle to manage apps of increasing complexity. You'll learn to:

* Add free and paid flavors to an app, and set up your build to share code between them
* Factor reusable functionality into a Java library
* Factor reusable Android functionality into an Android library
* Configure a multi-project build to compile your libraries and app
* Use the Gradle App Engine plugin to deploy a backend
* Configure an integration test suite that runs against the local App Engine development server

# Project Overview

When you're done, your multi-project build will look something like this. Proceed to the next slide for specific instructions.

![project overview](//lh3.googleusercontent.com/cJQtO_A08shKWZ1NEJxpvdYcfXxoHH87HYldIx_gOoGcoqnnZDTP3ycVqAnZSUMYzHygxhb-nEE_Yv_QmZY=s0#w=1920&h=1080)

### Supporting Courses
You should have the skills you need to complete this projcet after completing <a href="http://www.udacity.com/course/ud867-nd" target="_blank">Gradle for Android And Java</a>.
##How Do I Complete this Project?

### Step 0: Starting Point

This is the starting point for the final project, which is provided to you in the <a href="https://github.com/udacity/ud867/tree/master/FinalProject" target="_blank">course repository</a>.

It contains an activity with a banner ad and a button that purports to tell a
joke, but actually just complains. The banner ad was set up following the
instructions <a href="https://developers.google.com/mobile-ads-sdk/docs/admob/android/quick-start" target="_blank">here</a>.

You may need to download the Google Repository from the Extras section of the Android SDK Manager.

When you can build an deploy this starter code to an emulator, you're ready to move on.

### Step 1: Create a Java library

Your first task is to create a Java library that provides jokes. Create a new Gradle Java project either using the Android Studio wizard, or by hand. Then
introduce a project dependency between your app and the new Java Library. If you need review, check out demo 4.01 from the course code.

Make the button display a toast showing a joke retrieved from your Java joke
telling library.

### Step 2: Create an Android Library

Create an Android Library containing an Activity that will display a joke
passed to it as an intent extra. Wire up project dependencies so that the
button can now pass the joke from the Java Library to the Android Library.

For review on how to create an Android library, check out demo 4.03. For a
refresher on intent extras, check out <a href="http://developer.android.com/guide/components/intents-filters.html" target="_blank">this documentation</a>.

### Step 3: Create GCE Module

This next task will be pretty tricky. Instead of pulling jokes directly from
our Java library, we'll set up a GCE development server,
and pull our jokes from there. Follow the instructions in <a href="https://github.com/GoogleCloudPlatform/gradle-appengine-templates/tree/master/HelloEndpoints" target="_blank">this
tutorial</a> to add a GCE module to your project:

Introduce a project dependency between your Java library and your GCE module, and modify the GCE starter code to pull jokes from your Java library. Create an Async task to retrieve jokes. Made the button kick off a task to retrieve a joke, then launch the activity from your Android Library to display it.

### Step 4: Add Functional Tests

Add code to test that your Async task successfully retrieves a non-empty
string. For a refresher on setting up Android tests, check out demo 4.09.

### Step 5: Add a Paid Flavor

Add free and paid product flavors to your app. Remove the ad (and any
dependencies you can) from the paid flavor.

## Optional Tasks

For extra practice to make your project stand out, complete the following tasks.

### Add Interstitial Ad

Follow <a href="https://developers.google.com/mobile-ads-sdk/docs/admob/android/interstitial
" target="_blank">these instructions</a> to add an interstitial ad to the free version. Display the ad after the user hits the button, and before the joke is shown.

### Add Loading Indicator

Add a loading indicator that is shown while the joke is being retrieved, and
disappears when the joke is ready. <a href="http://www.tutorialspoint.com/android/android_loading_spinner.htm" target="_blank">This tutorial is a good place to start</a>.

### Configure Test Task

To tie it all together, create a Gradle task that:

1. Launches the GCE local development server
2. Runs all tests
3. Shuts the server down again

# Project Rubric

Your project will be evaluated by a Udacity Code Reviewer according to <a href="https://review.udacity.com/#!/projects/4295208853/rubric" target="_blank">this rubric</a>.

A summary of the rubric is provided below.

### Required Components

* Project contains a Java library for supplying jokes
* Project contains an Android library with an activity that displays jokes passed to it as intent extras.
* Project contains a Google Cloud Endpoints module that supplies jokes from the Java library. Project loads jokes from GCE module via an async task.
* Project contains connected tests to verify that the async task is indeed loading jokes.
* Project contains paid/free flavors. The paid flavor has no ads, and no unnecessary dependencies.

### Required Behavior

* App retrieves jokes from Google Cloud Endpoints module and displays them via an Activity from the Android Library.

### Optional Components

Once you have a functioning project, consider adding more features to test your Gradle and Android skills. Here are a few suggestions:

* Make the free app variant display interstitial ads between the main activity and the joke-displaying activity.
* Have the app display a loading indicator while the joke is being fetched from the server.
* Write a Gradle task that starts the GCE dev server, runs all the Android tests, and shuts down the dev server.

## Submission and Evaluation

Your project will be evaluated by a Udacity Code Reviewer according to the rubric in the previous node. Be sure to review it thoroughly before you submit. All criteria must "meet specifications" in order to pass.

**Note**:  Please make sure you **clean** your project before creating a zip file or pushing code to a GitHub repository. You can clean your project by following the instructions given in **[this](https://goo.gl/8lgeV5)** link.

If you are using GitHub to host your projects, please make sure the code you want to submit for review is in the **master** branch of your repository.

**IMPORTANT: If you're submitting via a public Github repository, please make sure any external API key that you utilize, has been removed from your code.**  It's highly unsafe (and often breaks the Terms of Service) to include API keys in public repos, so you need to remove yours. You can add a note in a README file where a reviewer should go to insert their API key. Reviewers have been trained to expect this situation.

When you're ready to submit your project, click on Udacity in the navigation bar at the top your screen to return to your Udacity Home. Then, locate and expand the project you'd like to submit. Click on the button to submit your project. You can view the submission process in more detail <a href="https://docs.google.com/document/d/1sfMGTlUxxkcZM6iRXbVZ45vPPZGRD4qEp3ENBGSmZ_o/pub?embedded=true" target="_blank">here</a>.

If you have any problems submitting your project, please email us at **android-project@udacity.com**. Due to the high volume of submissions, the turnaround for your project can take **up to a week**.

Each Android ND project will be reviewed against the<a href="http://udacity.github.io/android-nanodegree-guidelines/core.html" target="_blank"> Common Project Requirements</a>, in addition to its project-specific rubric.
