# OCR receipt

OCR example on a receipt
An example of text extraction using Optical Character Recognition (OCR) on a scanned image of a receipt.

Here we run through an example of extracting information from an image of a receipt. This is a typical difficult real world problem, but we show that with a few steps we can turn abysmal performance into something close to what we want. 

The general steps are as follows:

- Clean the image for easier OCR. Steps could include making the image binary; resizing the image; removing noise; morphological operations if the text hasn't scanned well; rotations to ensure text is horizontal. 
- Use OCR (HP/Google's Tesseract) for text extraction.
- Spell check to improve accuracy.
