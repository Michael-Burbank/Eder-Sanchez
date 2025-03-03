# Eder-Sanchez

<!-- TODO!: READ -->
***
Make sure to install Git LFS for the larger media file(s). Instructions below the Portfolio Website section.
***

<!-- TODO!: Tattoo Portfolio Personal Website -->

1. Website Sections:
    •Hero Section: Brief intro about the tattoo artist.
    •About Me: A section dedicated to introducing the tattoo artist.
    •Portfolio: Display of tattoo work and designs.
    •Contact: Information on how to reach out for inquiries.

2. Design and Branding:
    •Colors: Original Black and Grey tattoo designs.
    •Logo: Brand logo representation.
    •Linktree: Integration of social media links.
    •Business Questions: Section for any client inquiries or questions.

3. Website Sections (Optional):
    •Booking: Allows clients to schedule appointments.
    •Merchandise: Section for selling products.
    •Zelle / Paypal: Additional payment methods available on the website.

4. Tattoo Submission Process (Optional):
    •Radio Section for Ink Type: A required section for specifying the type of ink.
    •Select Input Menu: Option to choose the preferred ink type.
    •Image Submission: Option to submit an image for the tattoo design.

5. Availability (Optional):
    •Client Communication: The tattoo artist will reach out directly to clients for availability.
    •Calendar: Shows available time slots, with the option to lock in appointments with a deposit directly on the website.

6. Payment Methods (Optional):
    •Existing: Zelle, Cashapp.
    •To Explore: PayPal, Apple Pay.

7. Marketing and Advertising (Optional):
    •Ads: Consider running ads on Google, Instagram, and YouTube to promote services.

8. Instagram Widget (Optional):
    •Instagram Widget: Integration to display the latest Instagram posts directly on the website to enhance social media engagement.

<!-- TODO!: Repo Instructions: -->

## Install Git LFS

[Git LFS](https://git-lfs.com/)
Git LFS Setup for Large Files:

Using MacOS
    • Install Git LFS:
      brew install git-lfs
    • Initialize Git LFS in your repository:
      git lfs install
    • Track the large file `movie.mov` in the `Video` folder:
      git lfs track "Video/movie.mov"
    • Add the `.gitattributes` file to your repository:
      git add .gitattributes
    • Commit the changes:
      git commit -m "Track movie.mov with Git LFS"
    • Add and commit the large file:
      git add Video/movie.mov
      git commit -m "Add movie.mov"
    • Push the changes to the remote repository:
      git push origin main. \n

### Using Windows

    • Initialize Git LFS in your repository:
      git lfs install
    • Track the large file `movie.mov` in the `Video` folder:
      git lfs track "Video/movie.mov"
    • Add the `.gitattributes` file to your repository:
      git add .gitattributes
    • Commit the changes:
      git commit -m "Track movie.mov with Git LFS"
    • Add and commit the large file:
      git add Video/movie.mov
      git commit -m "Add movie.mov"
    • Push the changes to the remote repository:
      git push origin main
