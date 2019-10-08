# Object Detection Live Stream
![]()

## Setup
`git clone` the repo and `cd` into it by running the following command:

```bash
git clone https://github.com/cloud-annotations/object-detection-live-stream.git
cd object-detection-live-stream
```

### `npm install`

> **Note: You’ll need to have Node 8.10.0 or later on your local development machine.** You can use [nvm](https://github.com/creationix/nvm#installation) (macOS/Linux) or [nvm-windows](https://github.com/coreybutler/nvm-windows#node-version-manager-nvm-for-windows) to easily switch Node versions between different projects.

## Run the App
### `npm start`

Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

## Bonus: Add a Custom TensorFlow.js Model to the App
You can find an in depth walkthrough for training a TensorFlow.js model [here](https://github.com/cloud-annotations/training/).

Once trained, copy the generated `model_web` directory and paste it into the `public` folder of this repo.
