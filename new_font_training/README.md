The files that we have are scanned pdfs.   
Following are our observations on the files we worked with:
- Light vertical lines
- Border
- Typed Content, Cursive handwriting
- Skewed table
- Text very blur
 
We used the guidelines provided on tesseract-ocr github repo to improve the performance of OCR.   
[https://github.com/tesseract-ocr/tesseract/wiki/ImproveQuality#tools--libraries]

Still it was difficult to extract cursive handwriting and blurred text.
So, we attempted to add more fonts and train tesseract on those.
This would improve the results obtained through teserract for OCR.   

<b> Steps to train tesseract: </b>
The article (http://michaeljaylissner.com/posts/2012/02/11/adding-new-fonts-to-tesseract-3-ocr-engine) explains the process of training tesseract  
