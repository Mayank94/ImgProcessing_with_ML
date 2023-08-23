# Yoga Pose Detector

In the pursuit of spreading the benefits of yoga for physical and mental well-being, we present a revolutionary solution to bridge the gap between instructors and aspiring yoga practitioners. Our project, the **Yoga Pose Detector**, employs machine learning to enable users to upload images of themselves performing yoga poses. The system accurately identifies the pose and provides guidance for better practice.

## Motivation

Yoga, originating in India, offers profound health benefits, yet a significant portion of the population remains unacquainted with its potential due to the shortage of instructors. Our project aims to address this gap by using machine learning to act as a virtual instructor, enabling users to access and perform yoga poses correctly.

## Key Features

- **Pose Identification:** Our system can identify various yoga poses from user-uploaded images.
- **Guided Practice:** Not just identification, but also offers guidance to users on how to enhance their pose.
- **Diverse Models:** Utilizes a range of machine learning models, including classical PCA with KNN and deep learning CNN models.
- **MediaPipe Integration:** We achieve outstanding accuracy by leveraging Google's MediaPipe library, which employs deep learning to detect 33 landmark points on the human body, encompassing joints, hands, feet, and more.

## How It Works

1. **Image Upload:** Users upload images showcasing their yoga poses.
2. **Pose Detection:** MediaPipe's deep learning model identifies 33 key points on the body.
3. **Feature Extraction:** Landmark points are used to construct a skeletal model of the pose.
4. **Machine Learning:** Both deep learning (CNN) and classical ML (PCA with KNN) models are utilized.
5. **Pose Identification:** The system identifies the pose with exceptional accuracy.
6. **Guidance:** Tailored advice is provided on how to refine and improve the pose.

## Achievements

- **Accuracy:** Our deep learning model, combined with MediaPipe's landmark detection, achieves an impressive accuracy of 99% in pose identification.
- **Classical ML:** The classical machine learning approach, using PCA with KNN, attains an accuracy of 91%.
  

## Future Enhancements

- **Pose Variation Recognition:** Enhance the system to identify variations of a particular pose.
- **Multi-Person Detection:** Extend the model to detect poses for multiple individuals in a single image.
- **Mobile App Integration:** Develop a user-friendly mobile application for real-time pose detection and guidance.


## Conclusion

The Yoga Pose Detector project presents an innovative solution for making yoga accessible to all, irrespective of geographical constraints. By employing machine learning and deep learning models, we are not just identifying poses but also fostering correct practice. Our system has the potential to empower individuals to embrace yoga and lead a healthier life.

Join us in this journey towards spreading wellness through yoga!
