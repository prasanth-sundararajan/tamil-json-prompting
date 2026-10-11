# Tamil Kolam JSON Prompt

## What this project is

A prompt-writing and media-generation exercise about a Tamil kolam scene. [`tamil_prompt.json`](./tamil_prompt.json) describes the subject, setting, lighting, camera, colors, visual style, aspect ratio, and details to avoid. The folder also contains three generated images and a video.

## Check the JSON

From PowerShell in this folder:

```powershell
python -m json.tool .\tamil_prompt.json
```

If the file is valid JSON, Python prints the formatted content. A parsing error points to a place that needs correction.

## What to do

1. Review the prompt and make sure the scene details match the assignment.
2. Use the JSON as a guide in an image or video generation tool that accepts prompt text. JSON is not automatically executable by every image-generation tool; copy or adapt the prompt fields as that tool requires.
3. Review the three images and video for consistency with the prompt and for visual errors.
4. Keep the generated files that are required by the assignment and include a short note describing which image sequence was used to make the video, if requested.

Files currently included: `tamil_kolam_image_1.png`, `tamil_kolam_image_2.png`, `tamil_kolam_image_3.png`, and `tamil_kolam_video.mp4`.

## Task completed

The JSON prompt describes a Tamil kolam scene with details about the subject, location, time, lighting, camera, colors, style, and things to avoid. Three generated images and a video are saved with the project.

## Beginner task question

**Can you write a clear JSON prompt for an image-generation tool to create a culturally specific Tamil kolam scene, generate three related images, and use them to make a short video?**

Check that your JSON is valid, then adapt its details to the image or video tool you are using. Review the results to see whether they match the prompt.
