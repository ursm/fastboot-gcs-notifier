# FastBoot Google Cloud Storage Notifier

``` js
const GCSNotifier = require('fastboot-gcs-notifier');

const downloader = new GCSDownloader({
  bucket: 'bucket-name',        // required
  key: 'path/to/dist-xxxx.zip', // required
  authentication: {             // optional; see below
    projectId: 'project-id',
    keyFilename: 'path/to/key'
  }
});
```

For details on authentication, see [Google Cloud Node.js documentation](https://googlecloudplatform.github.io/google-cloud-node/#/docs/google-cloud/guides/authentication).