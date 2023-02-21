# NLP-ASR-NANO

A deep neural network that functions as part of an end-to-end automatic speech recognition (ASR) pipeline! Your completed pipeline will accept raw audio as input and return a predicted transcription of the spoken language. The full pipeline is summarized in the figure below.

![image info](./images/pipeline.png)

STEP 1 is a pre-processing step that converts raw audio to one of two feature representations that are commonly used for ASR.

STEP 2 is an acoustic model which accepts audio features as input and returns a probability distribution over all potential transcriptions. After learning about the basic types of neural networks that are often used for acoustic modeling, you will engage in your own investigations, to design your own acoustic model!

STEP 3 in the pipeline takes the output from the acoustic model and returns a predicted transcription.

- DNN Architectures tested
    - Model 0: RNN <br/>
    - Model 1: RNN + TimeDistributed Dense <br/>
    - Model 2: CNN + RNN + TimeDistributed Dense<br/>
    - Model 3: Deeper RNN + TimeDistributed Dense<br/>
    - Model 4: Bidirectional RNN + TimeDistributed Dense<br/>
    - Model 5: Deep Dilated CNN + Deep GRU + TimeDistruted Dense <br/>
- Compare the Models <br/>
- Final Model <br/>
- Predictions
