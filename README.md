# htmlToPngConverter

This <s>doubtful</s> script will download documents html previews from Docs API generate letter-size screenshots using puppeteer.

### How to use it:
Put desired documents template information into file ```name_templates_dds.txt```. Follow convention: template name | template UUID | template DDS.

Downloaded templates will be stored in ```htmlPreviews```.

Generated thumbnails will be stored in ```thumbnails```.

Please double check desired Docs API url in the main.js file.


### How to run:
install dependencies; run in the root folder:
```npm install```

run app:
```node main.js```

