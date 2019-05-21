# mp4-to-mpegdash-py
Python Script to convert a MP4 file into onDemand MPEG-DASH
## Dependencies 
* ffmpeg - https://www.ffmpeg.org/ 
* MP4Box - https://gpac.wp.mines-telecom.fr/mp4box/
## Setup
To upload the converted files to S3
`pip install -r requirements.txt`

## Usaage 
`$ python transcode.py $FILENAME`

### Acknowledgements 
This script is inspired from https://github.com/Cloudoki/mp4-to-mpegdash
