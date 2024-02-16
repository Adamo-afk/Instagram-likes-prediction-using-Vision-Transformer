# Likes-prediction-using-Vision_Transformer
The task was to create a multimodal system capable of predicting the specific category of a post and the possible number of likes that post can get from Instagram. The core objective was to leverage the visual and numerical data from social media posts to predict the popularity of content, measured in terms of number of likes. This involved understanding the relationship between the content of a post (landscapes or animals) and its engagement metrics (likes, comments, and distribution).

#**The inspiration**

The approach was inspired by the the paper “[Multimodal Post Attentive Profiling for Influencer Marketing](https://dl.acm.org/doi/fullHtml/10.1145/3366423.3380052)”, which utilized Inception-v3 for image encoding and BERT for the text of a post description. In the paper, a multimodal approach was employed for the task of influencer profiling. The change to a Vision Transformer architecture was motivated by its recent successes in various image-related tasks and its ability to handle images as sequences of patches, which aligns with the Transformer's sequence processing capabilities.
