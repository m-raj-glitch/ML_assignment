# Human Detection and Bounding Box Annotation

This Python script uses a pre-trained Faster R-CNN model from Torchvision to detect humans in a folder of images. It then adds bounding boxes around the detected humans and centers the boxes on the individuals. The annotated images are saved in an output folder.

## Prerequisites

Before running the script, make sure you have the following installed:

- Python (3.6 or higher)
- PyTorch (1.6 or higher)
- torchvision
- Pillow (PIL)
- [Optional] CUDA-enabled GPU for faster inference (recommended)


# Usage
 1. Clone this repository to your local machine or download the Python script.
 2. Organize your images in a folder (e.g., input_folder) that you want to process. The script assumes that the images are in JPG format.
 3. Open the Python script and set the following variables:
 4. input_folder_path: The path to the input folder containing your images.
 5. Output_folder: The path to the output folder where annotated images will be saved.
 6. confidence_threshold A threshold for human detection confidence (adjust as needed).
 7. Run the script using the following command:
      python human_detection.py
 8. The script will process each image in the input folder, detect humans, add centered bounding boxes, and save annotated images in the output folder.

# Output
Annotated images with centered bounding boxes around detected humans will be saved in the output_folder.

# Customization
You can further customize the script by modifying the code to change bounding box colors, line thickness, or other visual aspects.

