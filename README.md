# adaline_multiple_output

**It is desired to train a neural network to perform the separation of three audio sources that have been mixed into a single signal. The original signals come from three different sound sources: two of them from two people talking simultaneously and another source coming from a musical instrument or an audio track. The mixing of these signals has been done in a linear fashion, and the task is to recover each individual voice from the composite signal.
Tasks**

1. A mixed audio signal will be provided, composed of the different audio sources. Each of these audios has been linearly combined to form the observed signal. The audios should be picked up by the computer microphone.
2. Define the monolayer neural network and the input/output structure.
3. Train the network to approximate the three output signals, one for each original audio source.
4. Evaluate the performance of the network from the mean square error function.
5. Plot and reproduce the original audios and the network prediction.
6. Measure the quality of the separation using a metric such as the ratio between the recovered signals and the original voices.