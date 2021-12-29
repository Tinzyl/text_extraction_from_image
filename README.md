# text_extraction_from_image
### In this project, I used Tesseract and OpenCV to create a program that extracts text from images. The steps which were taken in developing this program were as follows:
- Load the image, resize it and then save it.
- Use the PyTesseract Library to extract the text from the image.
- Process the text extracted from the image.
- Used Computer Vision to perform further processing of complex images.
- Remove noise from the image using the blur function.
- Perform threshold transformation of the image.
- Use the erode function of cv2 on the image.
- Performed other image processing operations.
- Draw a rectangle around a character/word/pattern.

## Results

### Original Image: 

<img width="442" alt="Screen Shot 2021-12-29 at 3 45 26 AM" src="https://user-images.githubusercontent.com/18570056/147619688-0cba21a0-82be-4b5b-a49c-eec82274fb31.png">

### Text Extracted Using PyTesseract:

<img width="281" alt="Screen Shot 2021-12-29 at 3 44 04 AM" src="https://user-images.githubusercontent.com/18570056/147619633-e781e2b8-8eec-4764-bfc1-b953e37430c8.png">

The results were not quite accurate as it failed to get **to 54170 to join our text club**.

### Rectangle Drawn Around Text After Performing Computer Vision operations:

<img width="313" alt="Screen Shot 2021-12-29 at 3 48 48 AM" src="https://user-images.githubusercontent.com/18570056/147619830-9b86a85c-4f2b-449d-89d8-0e0763504001.png">

After performing Computer Vision Operations using OpenCV, the results were accurate as a rectangle was drawn around the text.

