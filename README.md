# SANDCAT (Segment ANything Does Collective Animal Tracking)
This is a work-in-progress pipeline to extract frames from a video using opencv then apply a Segment Anything Model to each frame to identify multiple animals. Ultimately, segmented frames will be combined and segments tracked to track multiple animals moving through frames of videos.

## Requirements
* A model from [Segment Anything](https://github.com/facebookresearch/segment-anything), placed in the 'Model' folder in your directory.
* Segment Anything version found here: [link](https://github.com/beckypadget/segment-anything) to be able to threshold max and min size of segments.
