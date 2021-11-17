## Installation
First make sure that [Node](https://nodejs.org/) is installed.
>Note: To check if Node is installed, open up a terminal and enter `node -v`.

If you see something like `vxx.xx.x`, you are good to go.
If you get an error instead, install Node following the instructions on the official [Node](https://nodejs.org/) website.

Now that you have Node installed, run `npm install`.
This will install all the required packages.

## Running the application
First make sure that [Parcel](https://parceljs.org/) is installed.

Type `parcel index.html` in the console to run the Parcel server.
Open [http://localhost:1234](http://localhost:1234) to view it in the browser.

>Some components rely on assets and ARC needs to know where they're located. 
Copy the `assets` folder from `@arc-web/components/dist` and place these in the `dist` output folder.