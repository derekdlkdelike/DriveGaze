# DriveGaze: A Gaze and Fatigue Prediction Dataset for Driving Scene

## Motivation

We are excited to announce the release of a new benchmark for Gaze and Fatigue Prediction in dashcam videos. Our dataset includes **3,182 videos**, comprising approximately **206K frames**. In this benchmark, annotators are presented with traffic accident videos where the ego vehicle will collide with other road participants. They are instructed to pause the video when they perceive the impending accident. During this process, the annotators' gaze locations are recorded until the video is paused. 

Each video is annotated by at least six licensed drivers, and we have specifically designed the study to include both **fatigued** and **vigorous** conditions. To the best of our knowledge, this is the first benchmark focused on traffic accident prediction through gaze and fatigue analysis. We hope it will provide valuable insights into these areas, which have been underexplored in the context of driving. Furthermore, we anticipate that it will contribute to advancements in understanding driving behavior and predicting driver habits in the future.

More details about the benchmark setup and our experiments on gaze and fatigue prediction will be available on **arXiv** soon.

---

## Dataset Statistics

### Gaze Data
- **General Setup**: A total of six annotators are involved, each annotating at least **(此处填写平均数)** out of the 3,182 videos. We have collected a total of **(此处填写现有总数)** human-annotated videos. The official training and testing splits will be released soon.
- **Cross-Person Evaluation**: Four additional annotators each annotate 260 unique videos, contributing a total of **1,040** human-annotated videos.

### Fatigue Data
- **General Setup**: We have gathered **14,170 videos** in total, with **6,630 videos** representing fatigue conditions and **7,540** for vigorous conditions. The official training and testing splits will be available soon.
- **Cross-Person Evaluation**: We have collected **1,040** videos, evenly divided between fatigue and vigorous conditions.

---

## Data Collection

### Hardware
- **Tobii Eye Tracker 5** for recording gaze location
- **Hikvision camera** for capturing facial information
- **Lenovo Legion Y9000P** for playing accident videos and recording human reactions  

*(此处可以有一张笔记本+摄像头+眼动仪组合在一起的照片，不用人脸)*

### Setup Details
1. **Psychomotor Vigilance Task (PVT)**: This task is used to measure the annotator's reaction time, helping to determine if they are fatigued or vigorous.
2. **Eye-Tracker Calibration**: The eye-tracker will be recalibrated every 5 minutes to ensure accuracy.
3. **Gaze Target and Reaction Time Collection**: The first frame of each accident video will be displayed for 3 seconds to allow the annotator to prepare. Afterward, the full video will play, and the annotator's gaze location will be recorded using the eye tracker. When the annotator detects the potential accident and pauses the video, their reaction time is captured. Following this, the next video will automatically begin.

---

## Examples

*(此处放一组example，依次为：)*

- 某张video frame
- video frame上gaze的location，即在前面一张video frame的gaze location位置画上红点表明此处为recrod的gaze
- 当前人脸图片 
- 当前人的PVT反应时间 与 这个video的reaction time。 这个写两个数字即可，不需要图片

---

## Reference

Our dataset will be available soon. Please contact us at **(此处添加作者邮箱cichu)** for more details.
