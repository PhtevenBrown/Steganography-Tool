# How to run:

<h3>Hiding</h3>

Open and run the `HideData` java class, this will ask you in the terminal to input the name of the bmp file that you want to use as the cover image, and then the payload.

E.g our test cover image is `stegg.bmp` and our test data is `payload.txt`
This will save a stego-object called `output.bmp`

<h3>Extracting</h3>

Open and run the `ExtractData` java class, this will automatically take in the `output.bmp` file and return the payload calling it `extracted_data` with original extension.
