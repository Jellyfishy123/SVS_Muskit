### **Contributors:**
SJT Music Team Jiatong Shi, taken from https://github.com/SJTMusicTeam/Muskits
<br> Google colab demo file is here https://colab.research.google.com/github/SJTMusicTeam/svs_demo/blob/master/muskit_svs_realtime.ipynb

Nguyen Tien Dat

### **About:**
Hey everyone, so I found another model and it work extremely well and I'm very pleased. The original file runs when the file path of the songs are provided (as in original code) and specific inputs. However, I did not use a file path and instead manually refine the data set to make my version of music_score, duration_info and text so I can feed them into the training model. This took me a lot of work but in the end, the sound quality was not what I expected so I think I might have made an alignment error somewhere. However, this process is very intensive and tasking as it requires very specific inputs (TextGrid file, wav file, midi file) plus human interaction to test the model. Furthermore, the sound quality of the original is not the best but it's certainly not the worst either. To make matter worse, I use "2001.TextGrid", "2001.midi" and "2001.wav" as my inputs into the sing_generation function and it took up to 4 minutes for just a song. There are 100 songs in total so yes, getting all the songs (not at best quality) will cost us quite a bit of time. Hence, I will continue to explore other models. This model uses a lot phonemes so I'll hoping to move away from it. Please reach out to me (tiendat311003@gmail.com if you have any information. Thank you for reading!


