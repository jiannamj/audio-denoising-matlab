# audio-denoising-matlab
ABOUT THE PROJECT:
● The project focuses on removing unwanted noise from audio signals to improve clarity using wavelet thresholding.
● The MATLAB script applies wavelet decomposition and soft thresholding to filter out noise from a noisy audio signal.
● This is used in various applications , such as music production, speech recognition, and hearing aids, where clear audio is essential.

STEPS FOLLOWED:
STEP 1: First, we load the audio sample from the selected file using MATLAB's file dialog.
STEP 2: Next, we play the original audio to listen to the unprocessed sound.
STEP 3: Then, we introduce Gaussian noise to the original audio signal to simulate a noisy environment.
STEP 4: After adding noise, we play the noisy audio to hear the effect of the noise.
STEP 5: For denoising, we apply wavelet thresholding to estimate and suppress the noise in the signal.
STEP 6: We normalise the denoised audio and adjust its gain to ensure proper loudness and avoid distortion.
STEP 7: The denoised audio signal is then played to demonstrate the effect of noise reduction.
STEP 8: Finally, we plot the original, noisy, and denoised audio signals in separate graphs for visual comparison.
STEP 9: Additionally, we can also save the denoised audio if required.
