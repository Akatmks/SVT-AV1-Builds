# SVT-AV1-Builds

Welcome to our build repository!  

We've finally finished our GitHub Actions based fully automatic [building script](https://github.com/Akatmks/build-svt-av1). By utilising the best compiler and best procedure, including LTO and PGO, our building script creates highly optimised builds within 2% of the best possible build.  

Major SVT-AV1 variants have adopted this building script, and now provide optimised builds on their repository directly. In the next section you'll be able to find links to their GitHub Releases page.  

## Latest builds we recommend

If you come from the GitHub Release page that recommends you to use a fork instead of mainline SVT-AV1, here is our recommendations.  

All of these forks focus on improving visual quality you can see with your eyes, and have good defaults where you only need to specify a few basic parameters to get the best result.  

* **5fish/SVT-AV1** is a SVT-AV1 variant that excels at 2D content, especially anime and some gaming footage.  
  * README: https://github.com/5fish/SVT-AV1#5fishsvt-av1  
  * Latest builds: https://github.com/5fish/SVT-AV1/releases  
* **SVT-AV1-HDR** is a SVT-AV1 variant that excels at liveaction or other 3D content, as well as content with heavy film grain.  
  * README: https://github.com/juliobbv-p/svt-av1-hdr#svt-av1-hdr  
  * Latest builds: https://github.com/juliobbv-p/svt-av1-hdr/releases  
* **SVT-AV1-Tritium** is a variant of SVT-AV1-HDR. It adds upon it and provides additional useful features from SVT-AV1-Essential.  
  * README: https://github.com/Uranite/svt-av1-tritium#svt-av1-tritium  
  * Latest builds: https://github.com/Uranite/svt-av1-tritium/releases  
  
## Builds provided in this repository

Currently, this repository provides builds for latest SVT-AV1-Essential, builds for mainline SVT-AV1, and archival builds for older versions.  

* **SVT-AV1-Essential** is a variant of SVT-AV1.  
  * README: https://github.com/nekotrix/SVT-AV1-Essential#svt-av1-essential  
  * Latest builds: https://github.com/Akatmks/SVT-AV1-Builds/releases?q=SVT-AV1-Essential&expanded=true  
* Mainline **SVT-AV1**:  
  * README: https://gitlab.com/AOMediaCodec/SVT-AV1#scalable-video-technology-for-av1-svt-av1-encoder  
  * Latest release builds: https://github.com/Akatmks/SVT-AV1-Builds/releases?q=Mainline+SVT-AV1+Release&expanded=true  
  * Semimonthly git HEAD builds: https://github.com/Akatmks/SVT-AV1-Builds/releases?q=Mainline+SVT-AV1&expanded=true  
* Archival builds:  
  * We provide archival builds for mainline SVT-AV1 since v1.8.0, original SVT-AV1-PSY, SVT-AV1-HDR, SVT-AV1-PSYEX, and SVT-AV1-Essential. Using this new building script, we provide a build for every minor version. As an example, we have a mainline SVT-AV1 v3.1.2 build, then before that it is SVT-AV1 v3.0.2.  
    However, we've been using this repository to distribute manual PGO builds before the implementation of the new building script. You will be able to find a lot of older builds here as well.  
  * Search for the variant you're looking for in our GitHub Releases page: https://github.com/Akatmks/SVT-AV1-Builds/releases  
