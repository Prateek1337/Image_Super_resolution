# Image_Super_resolution

## [For h5 files click here](https://drive.google.com/drive/folders/15YH9yWSh6IjmZiWL1xh5rRtIPnEgLkPh)

Overview:

Image super resolution aims in recovering a high resolution image from a low resolution one.Our method directly learnsand end to endmapping between the high/low- resolution images. The mapping is represented as a deep Convolution Neural Network that takes the low resolution image as input and outputs a high-resolution one . We explore different network structures and parameter setting to achieve trade offs between speed and performance.

We conducted experiments from [this paper](https://arxiv.org/abs/1501.00092).

We first tested different filters. We tried the following combinations:

***NOTE:*** *We have used <ins>T91 dataset</ins> for the following results.*

A.  **915 :**

Comparing PSNRs between Bicubic and our SRCNN for YCrCCb:

Bicubic: 32.053059313091204

SRCNN: 33.56075266205568 

Input:

![Input to the 915](https://user-images.githubusercontent.com/60055090/75880698-c63e1a80-5e43-11ea-9f82-7d32112dcee9.png)

Output:

![Output of the915](https://user-images.githubusercontent.com/60055090/75880725-d48c3680-5e43-11ea-878d-b197bc7eef0c.png)



B.  **935 :**

Comparing PSNRs between Bicubic and our SRCNN for YCrCCb:

Bicubic: 32.053059313091204

SRCNN: 33.68691645424939

Input:

![Input to the 935](https://user-images.githubusercontent.com/60055090/75880701-c807de00-5e43-11ea-8319-e2b7dd72b8ee.png)

Output:

![Output of the935](https://user-images.githubusercontent.com/60055090/75880731-d5bd6380-5e43-11ea-927f-6c26873b671a.png)

C.  **955 :**

Comparing PSNRs between Bicubic and our SRCNN for YCrCCb:

Bicubic: 32.053059313091204

SRCNN: 33.616639192529114 

Input:

![Input to the 955](https://user-images.githubusercontent.com/60055090/75880702-c9390b00-5e43-11ea-9339-0e4969a0e875.png)

Output:

![Output of the955](https://user-images.githubusercontent.com/60055090/75880733-d6ee9080-5e43-11ea-95b7-e9f8c8a72974.png)

**Comparing three of them :**

![Screen Shot 2020-03-04 at 4 55 39 PM](https://user-images.githubusercontent.com/60055090/75876974-ae16cd00-5e3c-11ea-8a51-76629188d0aa.png)







 
