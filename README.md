# BinBuddy

🏆 **Won Most Technical Hack at Hack CLT**

Not sure if something's recyclable? Snap a photo. BinBuddy classifies the item, asks a
quick follow-up question when needed ("Is the cardboard greasy?"), and rewards correct
recycling with points students can redeem for prizes.

## How it works
- **Model**: MobileNetV2 transfer learning (ImageNet weights, frozen base + custom dense head),
  trained on a multi-class waste dataset with augmentation; exported to H5 and TFLite
- **API**: Flask `POST /predict` endpoint takes an image and returns the predicted class + confidence
- **App**: React Native (Expo) with camera capture, category-specific follow-up questions,
  and a points/rewards system

## Stack
TensorFlow/Keras · Flask · React Native · Expo · TypeScript

## Team
Vedanth Shenoy, Simran "Summer" Malik, Sai Pradyumna Mudigonda, Veer Pothapragada, Dev Patel.
All five of us worked across the model, API, and app.

Category: Sustainability
