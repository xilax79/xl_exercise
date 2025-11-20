# Architectural Exercise: Uploading Big Files (AWS)

## The Assignment

> You just joined a project and they are experiencing an issue with file uploads. The product has a functionality where users can upload images, which is currently implemented by having the user upload the file directly to the backend, which runs inside a basic EC2 machine, where it is then uploaded to Amazon S3. As of late they have had to restart the backend multiple times since it keeps increasing disk swap space. The client has told you that a couple of weeks ago they released a feature which allows users to upload videos, and they have reused their implementation for images. Describe briefly what you think the issue is. Feel free to make any assumptions you need to, but make sure to document them in your solution.
>
> How would you solve the issue?
>
> For background video processing, would you recommend Celery, RQ, or async/await? Justify your choice considering scalability and complexity, and explain what design patterns you would apply to make this system maintainable and extensible based on your technology choice.

## Solution

It is detailed in the **`solution.html`** file located in this repository.