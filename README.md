## Project overview:

__Introduction:__

In response to the challenge faced by online businesses like Shopee, the task is to identify near-duplicate products within a large dataset. This task becomes more complex due to the diverse user-generated content, including images and product descriptions. The goal of this competition is to develop a machine learning model that can accurately identify products that have been posted repeatedly, even when they may have subtle differences in images, titles, or descriptions.

__Data Description:__

The dataset contains metadata and images of products posted on Shopee's platform. Each row contains the data for a single posting. __Multiple postings might have the exact same image ID, but with different titles or vice versa__. Each entry includes the following information:

| Variable | Description|
| --- | --- |
| posting_id | the ID code for the posting.
| image | the image id/md5sum.
| image_phash | a perceptual hash of the image.
| title | the product description for the posting.
| label_group | ID code for all postings that map to the same product. Not provided for the test set.

[Link: Shopee's business case](https://www.kaggle.com/competitions/shopee-product-matching/data)
