# AI in the classroom: tools and strategies for teaching and assessment

## Introduction

### Icebreaker and quizzes
www.menti.com

## Language models

### Task
**Create an open cloze exercise from the following text. Use a language model to identify optimal gap candidates.**

Maria's working knowledge of Chinese led her to a chance encounter in a tea shop. Impressed by her fluency, an art dealer offered her an apprenticeship in Beijing. Her life transformed as she immersed herself in Chinese art, becoming a renowned curator whose expertise knew no borders.

### BERT
https://huggingface.co/xlm-roberta-large (multilingual)  
https://huggingface.co/spaces/UserConfused/bert-base-uncased  
https://huggingface.co/spaces/docs-demos/bert-base-uncased  
https://huggingface.co/bert-base-uncased  
https://huggingface.co/bert-large-uncased  

### GTP-2 next word predictors
https://huggingface.co/spaces/Bhagu69/next-word-fun  

### N-gram next word predictors
https://fschoen.shinyapps.io/NextWordPrediction/  
https://philferriere.shinyapps.io/WordPredictR/

## Automated essay scoring

### Quiz
**Choose the most appropriate CEFR level for a short student essay.**

In today’s world, the fashion industry has a strong importance in people’s lives. The fashion industry say to the society what to wear and creates new types of clothes all the time.  
Some people claim that the fashion industry has a bad effect on people’s lives, they say that the fashion industry creates clothes that the society has to wear. Furthermore, the clothes’ price is extremely high and people, who can’t afford it, should not be in the society.  
In the other hand, the fashion industry guide the people to be in a good appearance, because, nowadays, the appearance of the person is more important than the person itself.  
In my opinion, the fashion industry doesn’t has a bad influence on people’s lives. It’s something which was created to help people what to wear.  

### Write&Improve
https://writeandimprove.com/workbooks#/wi-workbooks

## Grammatical error correction

### Task
**Correct the following essay:**

My favourite season of the year is summer. I think that most of the people love summer, especially the people in Greece. I dont know why but the summer it is the most beautiful season.  
I live in Greece, and especially in an island, so I know very well what summer means. It means swimming at the wonderfull beaches, tasting the delicious foods ad having wonderful time every day and every night with your friends.  
I think that the summer makes people to feel great, to have fun, to enjoy themselves. I believe that the summer is a season for everybody who wants to have wonderful time and wonderful memories wherever the go.  

### Online grammar checkers
**Grammarly:** https://www.grammarly.com/grammar-check  
**QuillBot:** https://quillbot.com/grammar-check  
**Ginger:** https://www.gingersoftware.com/grammarcheck  
**Linguix:** https://writer.com/grammar-checker/  
**ProWritingAid:** https://prowritingaid.com/grammar-checker  
**PaperRater:** https://www.paperrater.com/free_paper_grader  
**Reverso:** https://www.reverso.net/spell-checker/english-spelling-grammar/  


### ERRANT
https://nlptoolbox.cl.cam.ac.uk/errant/

## Automatic speech recognition
**Task**
1. Listen to the following audio clip and manually transcribe what you hear.
2. Use an ASR service to generate an automatic transcription of the audio.
3. Compare both transcriptions and compute a word error rate (WER).

https://github.com/mfelice/ndea2023/assets/11545607/6e04db93-05f3-4ea6-afab-5826e84a93e9

Download the audio file: [here](https://filebin.net/o7fq43zgxtufoonv/asr-audio-clip.mp3)

### ASR services
**OpenAI Whisper**   
https://huggingface.co/spaces/sanchit-gandhi/whisper-jax  
https://huggingface.co/spaces/hf-audio/whisper-large-v3  
https://deepinfra.com/openai/whisper-large  
**AssemblyAI:** https://www.assemblyai.com/playground/source  
**VoiceGain:** https://demo.voicegain.ai/  

### WER calculator
https://www.amberscript.com/en/wer-tool/

## Speech synthesis (text to speech)
### Task
Create a listening comprehension question consisting of a dialogue between three people with different accents.

1. Create a short dialogue and question.
2. Create an audio file for each turn of the conversation using a TTS service.
3. Join all the audio files together.

**Sample dialogue**  
Ani is from Australia, Ben is from the UK and Chaya is from India.  

**1-A:** Hi guys, how are you doing?  
**2-B:** Hi Ani, not bad, thanks.  
**3-C:** Yeah, all good. How about you?  
**4-A:** A bit stressed to be honest... I've got my driving test today.  
**5-B:** Really? I thought it was next week!  
**6-A:** It was, but they changed it.  
**7-C:** That's unfortunate. But you've practised a lot, I'm sure you'll pass!  
**8-A:** I hope so!  

**Question**  
Ani is going to take a driving test. Why is she stressed about it?

a) She hasn't practised much.  
b) Her test has been postponed until next week.  
d) Her test is today.  
c) She is not confident she will pass.  

### TTS services
https://freetools.textmagic.com/text-to-speech  
https://ttsfree.com/  
https://ttsmp3.com/  
https://ttstool.com/  
https://huggingface.co/spaces/elevenlabs/tts  
https://freetools.textmagic.com/text-to-speech  
https://speechgen.io/

### Audio joiner
https://audio-joiner.com/

## Large language models

### LLMs
**ChatGPT:** https://chat.openai.com/  
**Bing Chat (GPT-4):** https://www.microsoft.com/en-us/edge/launch/bing-chat-features?form=MT00IR  
**ChatGPT (no registration, unofficial):** https://chat.chatgptdemo.net/ https://talkai.info/chat/  
**Llama 2:** https://labs.perplexity.ai/ https://www.llama2.space/  
**Claude:** https://claude.ai/  

### Task I
Can you guess who wrote these texts?
A human or a machine?

**Passsage 1**  
Every country in the world suffers environmental catastrophes. This is a natural consequence of the struggle between development and environment. If a country decided to live isolated from the rest of the world, living on what it can naturally grow and produce, it surely wouldn’t be highly polluted. But we all want exotic food and technological items from all over the world, so we have to pay the price. Investing on electrical transport would benefit the environment a lot. Even more if this electricity came from a natural source of energy like wind, rivers and solar boards. We also have to take care of our rivers and seas. We all have heard about factories throwing highly toxic substances to rivers, without minimizing their poisoning effects. A really strict law should be applied to fine these factories and make them change their policy.

**Passsage 2**  
Global warming is a serious issue that affects the entire planet. The Earth's temperature is rising because of human activities. When we burn fossil fuels like coal, oil, and gas, harmful gases are released into the atmosphere. These gases trap heat from the sun and cause the Earth to become warmer. This leads to various problems such as melting ice caps, rising sea levels, and extreme weather events. It is important to reduce our carbon footprint by using less energy and finding cleaner sources of power. We can also make a difference by recycling, conserving water, and protecting natural habitats. Taking action against global warming is crucial for the well-being of our planet and future generations.

**Passsage 3**  
Society has a responsibility to take care of the environment. We all live on this planet, so it's important for us to do our part to keep it clean and healthy. There are many things we can do to be environmentally responsible. We should recycle our waste, such as paper, plastic, and cans, instead of throwing them away. It's also important to save energy by turning off lights and appliances when we're not using them. Using public transportation or carpooling can help reduce pollution from cars. We should also avoid wasting water and try to conserve it. Planting trees and taking part in community clean-up activities are great ways to contribute to a cleaner environment. By being environmentally responsible, we can make a positive impact on our planet and ensure a better future for ourselves and future generations.

### AI content detectors
https://gptzero.me/  
https://writer.com/ai-content-detector/  
https://contentatscale.ai/ai-content-detector/  
https://www.wordtune.com/ai-content-detector  
https://undetectable.ai/  
https://originality.ai/ (paid)  

### Task II

Can you “humanise” the following AI-generated text?
Can we fool detectors?

**The Importance of Art**

Art is a vital part of human life. It offers many benefits to individuals and society as a whole. One of art's most important roles is as a universal language that can bridge cultural gaps and foster understanding among diverse communities. Art also provides a unique way to express emotions and explore oneself.

In education, art can enhance cognitive development, creativity, and problemsolving skills. It can also beautify our surroundings and instill a sense of pride and cultural identity within communities. Furthermore, art can challenge societal norms and encourage critical thinking, making it a catalyst for social change and progress.

In essence, art is more than just a form of entertainment; it is a powerful tool that can enrich lives, promote empathy, and nurture creativity. By embracing art in all its forms, we can enhance our collective human experience and create a more vibrant and culturally rich society.

### AI text "humanisers"
https://undetectable.ai/ (paid)  

### Task III  
Can LLMs score texts by their CEFR level?  
Is it accurate? How can you make it better?  

## Text to image

### Task
Can you write a prompt to generate an image like this one?  

![picture](https://github.com/mfelice/ndea2023/assets/11545607/aadd2fe3-9ad6-4c3c-b5a1-41d090ad45a1)

### AI image generators
**DALL·E:** https://labs.openai.com/  
**Stable Diffusion:** https://stablediffusionweb.com/#demo https://huggingface.co/stabilityai/stable-diffusion-xl-base-1.0 https://huggingface.co/spaces/songweig/rich-text-to-image  
**Openjourney 4:** https://huggingface.co/prompthero/openjourney-v4  
