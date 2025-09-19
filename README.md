# Text-to-video-LLM
<br>
<br>
<p> I have built an model using LLMs like ZeroShotDiffusion model and CLIP model that takes in a text and generates a video.</p>
<br>
<p> I used CLIP model to measure the correctness of the prompt for the image. Then, I used the concept of tensors for storing the probabilties of each of the prompt text that comes as an output of the model. For example, I give the image of a cat, then give the prompts ["a photo of a cat", "a photo of a dog"]. The CLIP model assigns probabilties to each of the prompts which are stored in a tensor.</p>
<br>
<p> To evaluate and fine-tune the model, I used the concepts of parameters like LORA and QLORA.</p>
<br>
<p> The model is solely built using Python by utilizing the Torch library, LLMs, numpy, skimage and so on.</p>
