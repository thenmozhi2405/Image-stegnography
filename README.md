# Image-stegnography
This project aims to develop an image 
steganography technique for secure communication, applicable 
across diverse fields such as the military, medical, financial, and 
legal domains. The primary objective is to securely embed 
sensitive data, including classified information, personal records, 
or confidential images, into a cover image in a way that is 
imperceptible to unintended recipients. To achieve this, we employ 
a combination of Discrete Wavelet Transform (DWT) and 
Singular Value Decomposition (SVD). DWT is utilized to 
decompose the cover image into multiple frequency components—
 approximation, horizontal, vertical, and diagonal details—thereby 
enabling selective and efficient embedding. The frequency domain 
offers improved resistance to attacks and compression. SVD 
further processes these decomposed components, breaking them 
into matrices of singular values that are then manipulated to 
embed secret information. The embedded data can be reliably 
recovered during the decoding phase, ensuring data integrity and. 
This method is designed to overcome the limitations of traditional 
techniques, such as the Least Significant Bit (LSB) method, which 
is more susceptible to distortions and attacks. By incorporating 
DWT's multiresolution analysis and SVD's precision in matrix 
manipulation, our approach enhances embedding capacity, 
resistance to attacks, and image quality retention. To evaluate the 
performance of our method, key metrics such as SQNR, PSNR, 
correlation coefficient, SSIM, and histograms are analysed. These 
metrics confirm the superiority of our technique in achieving a 
balance between security and fidelity, making it a versatile and 
reliable solution for secure data transmission. 
