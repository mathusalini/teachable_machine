# teachable_machine

Teachable Machine is a web-based tool developed by Google that allows users to create machine learning models without any coding knowledge. It's designed to make machine learning accessible to anyone by providing a simple and intuitive interface. You can train models using images, sounds, or poses, and then use those models in real-world applications such as websites, apps, or even hardware devices.

The interface is designed for non-programmers, so you don't need any coding experience to create a machine learning model. 😊 Simply provide examples of what you want the model to learn, and it will do the rest.

## Types of Models:

- **Image Classification**: Train the model to recognize different objects or categories using images (e.g., distinguishing between different types of bottles).
- **Sound Recognition**: Train the model to recognize sounds or different audio inputs (e.g., clapping vs. snapping).
- **Pose Detection**: Train the model to recognize specific human poses through the webcam (e.g., standing vs. sitting).

## How It Works:

- **Input Data**: You upload images, record sounds, or provide webcam input for training.
- **Training**: The system trains a model based on the examples you provided, recognizing patterns in the data.
- **Exporting**: Once the model is trained, you can export it to use in your own projects. Teachable Machine supports export to platforms like TensorFlow.js (for websites), TensorFlow Lite (for mobile devices), and even Coral (for edge devices).


![Screenshot4](https://github.com/user-attachments/assets/4b9f4f71-90cb-4294-8fd2-3cc9ed04e10a)

## No Installation Required:

Everything runs in your browser, so you don’t need to install any software. All data is processed locally, keeping it private and secure.

## Use Cases:

- Educators can use it to teach the basics of machine learning.
- Artists can create interactive installations.
- Developers can integrate the models into their applications.

## Example Workflow:

1. **Collect Data**: Upload images, record audio, or show poses to your webcam.
2. **Train Model**: Teachable Machine trains a machine learning model on this data.
3. **Test & Refine**: You can test the model in real-time and adjust the data if necessary.
4. **Export**: Once satisfied, export the model for use in web apps or other platforms.


# How to Create and Train a Model in Teachable Machine

In this tutorial, we will create a machine learning model using Teachable Machine to classify two categories: **Water Bottles** and **Stationary Items**. This can be useful in online study classes to analyze what students are using.

## Step 1: Create a New Teachable Machine Project

Go to the [Teachable Machine](https://teachablemachine.withgoogle.com/) website and click on **Get Started**. Choose the **Image Project** option.


## Step 2: Create Classes for Water Bottles and Stationary Items

Once you’re in the image project, you'll need to create two classes:

1. **Water Bottles**: Upload images or drag and drop them into the first class. You can either upload them from your device or import from Google Drive.

![Screenshot0](https://github.com/user-attachments/assets/0d4444e8-323c-42c1-82a0-93f5c0997b98)

2. **Stationary Items**: For the second class, upload images or drag and drop them for stationary items like pens, rulers, erasers, etc.

![Screenshot1](https://github.com/user-attachments/assets/225eaade-23d4-48ca-8e04-e6028c9d2757)

## Step 3: Upload Image Samples

For each class, make sure to add a variety of images to help train the model accurately. You can add as many images as you have. The more diverse the images, the better the model will perform.

Here are examples of image samples for both classes:
- **Water Bottles**: Images of different types of water bottles (plastic, metal, etc.)
- **Stationary Items**: Items such as pencils, pens, rulers, and erasers.

## Step 4: Train the Model

After uploading the images, click the **Train Model** button. Teachable Machine will process the data and start training based on the provided examples.

![Screenshot2](https://github.com/user-attachments/assets/4b828980-de49-4d8f-8fb7-07f0ac46b934)
## Step 5: Test and Export the Model

Once the training is complete, you can test the model in real-time using your webcam or uploading new images. Test to see if it can distinguish between water bottles and stationary items.
![Screenshot3](https://github.com/user-attachments/assets/166775df-3234-4b40-bb0f-1f98e5646761)

If you’re satisfied with the results, you can export the model to use in your own web projects, applications, or even in hardware devices using platforms like TensorFlow.js or TensorFlow Lite.

---

By following this process, you will be able to train a simple image classifier that can help you analyze what objects are being used in your online study classes. With real-time testing, you can check whether the student is using a water bottle or a stationary item in the live feed.

