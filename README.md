## live-ASR
I used *whisper* V3, an open source model by openAI. There are a lot of projects on github built around whisper. I used the simplest one I could find.
It uses the *transformers* library from hugging face for easy access to the model and *Gradio* for easy demonstration. There are two options : to live transcribe or to upload an audio file.
I used colab's T4 GPU. One version of the demo used flash attention and A100 GPU, which works fine too.


Run ASR_demo.ipynb in google colab. Configure a token with read permissions on Hugging face and add it to your colab notebook secrets, this will allow colab to access Hugging face models. Use T4 GPU or A100 GPU from the Colab runtime.
