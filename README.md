Flower Image Classification Using Convolutional Neural Networks (CNN) and TensorFlow! This project showcases a robust system that accurately categorizes flower images into five distinct classes: Daisy, Dandelion, Roses, Sunflowers, and Tulips.



🌿 Project Stages:



1️⃣ Data Acquisition:

The project commenced by acquiring the flower images data, which was in the tgz format. Following the data download, I embarked on a comprehensive exploration of the images, gaining a deep understanding of their characteristics and visual attributes.



2️⃣ Dataset Creation:

Subsequently, I created a meticulously organized dataset comprising separate sets for training, validation, and testing. The powerful TensorFlow library facilitated this process through its efficient image_dataset_from_directory function. To optimize the performance of the datasets, I leveraged TensorFlow's features such as td.data.AUTOTUNE, cache(), and prefetch().



3️⃣ Model Development and Maintenance:

The project then progressed through three crucial stages of model development and maintenance, ensuring optimal performance and accuracy.



  - 1️⃣ Standard Model Development:

   In this phase, I constructed a deep learning model as a baseline for evaluation.



  - 2️⃣ Overfitting Mitigation:

   To address the challenge of overfitting and further enhance the model's classification accuracy, I implemented advanced techniques. These included regularization, dropout, and early stopping mechanisms. By incorporating these techniques, the model achieved better generalization and minimized the risk of overfitting.



  - 3️⃣ Data Expansion:

   In order to enrich the training data, I expanded the dataset by scraping an additional 5,000 diverse flower images from the internet, obtaining approximately 1,000 images for each flower class. These augmented images were then combined with the original dataset, enhancing the model's training process.(https://drive.google.com/file/d/1uht92rhzqDVxpD44fwkC4AjuRC2tO0nj/view?usp=sharing)

