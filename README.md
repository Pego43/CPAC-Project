# FEEL THE DATA 
![Thumbnail](https://github.com/Pego43/CPAC-Project--Feel-The-Data/assets/48025739/19fe9bd8-86c3-4ffd-958b-1dd2ec4969fe)

### Summary
1. [Authors](#authors)
2. [Abstract](#abstract)
3. [Description](#desc)
4. [Challenges](#chal)
5. [Technology](#tec)
6. [Link](#projectlink)

### Authors <a name = "authors"></a>
- Eutizi Claudio
- Perego Gabriele
- Ricard Plandolit
- Zezza Federica


### Abstract <a name = "abstract"></a>
A machine learning-powered platform to make users feel the
evolution of data through time and hear the impact of such data through emotion.

### Description <a name = "desc"></a>
A machine learning-based data sonification and visualization web app to
map data to music and image, generating a ’data experience. The project is meant for
anyone that is able to interact with a web app, from very young people (as it is almost
usable just by looking at the images) to older ones
Our goals are:
  - To educate the highest number of people possible: to inform the young generations and to get detached people interested in today’s issues.
  - To make an extendible platform.
  - To make data understandable without having to know specific concepts.

![Screenshot1](https://github.com/Pego43/CPAC-Project--Feel-The-Data/assets/48025739/2df71dd4-40ff-4536-a23d-6558b74ab881)

![Screenshot2](https://github.com/Pego43/CPAC-Project--Feel-The-Data/assets/48025739/901fa7e6-48d3-4855-bf0b-eb80d69315a9)

![Screenshot3](https://github.com/Pego43/CPAC-Project--Feel-The-Data/assets/48025739/ca8a5a3e-3e84-49d3-9465-97d250965043)

### Challenges <a name = "chall"></a>
One of the main challenges we run into has been not being able to work physically
together and divide the work in such a way that it could be easily merged.  
Another issue was automatic music composition. At first, we wanted to use a model
(Riffusion) that created complete musical loops using spectrogram images to generate
sound.  
But after some time we understood that it was too much work for the time we
got. So we decided to go with Magenta which has libraries and models easy to use and
understand.  
Lastly, we run into some issues using a framework that allowed us to have a big particle
system that could run in a browser without having performance issues. We solved the
problem by choosing a vanilla javascript algorithm.

### Technology <a name = "tec"></a>
For the map: p5.js, mappa.js, and the Mapbox API.  
For the music: magenta.js, specifically the magenta RNN and magenta music VAE.  
We applied the valence-arousal plane concept to map the data to music.  
For the data: OpenWeather API, specifically the Current Weather Data API and Air Pollution API.  
For the visuals: plain javascript, the OpenAI Dall-e API, and the concepts of Particle systems and Perlin noise.  
The whole project is hosted in a Node.js application.

### Links <a name = "projectlink"></a>
http://feel-the-data-rick1080p.onrender.com/

