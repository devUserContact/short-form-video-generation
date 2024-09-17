# Short Form Video Generation

## a terminal workflow that uses bash and ffmpeg to generate short from video for social media

### What is needed for this workflow:

    * one long form video file
        * over two minutes in duration
    * one mp3 file
        * under one minute in duration

### shell script directions

Put audio and video files into the `00_original` directory

From the `_default` directory, execute the shell script :

```bash
$ sh avProcess.sh create
```

When the script is complete the generated videos will be available in the `FINAL` directory
