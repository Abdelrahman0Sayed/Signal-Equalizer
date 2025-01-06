# Signal Equalizer Application

## Introduction

The Signal Equalizer is a versatile desktop application designed for modifying the magnitude of specific frequency components in audio and other signal types. This tool is widely used in music, speech, and biomedical applications, such as hearing aids and ECG analysis.

## Features

1. **Multiple Modes of Operation**:
   - **Uniform Range Mode**: Divides the total frequency range into 10 equal segments, each controlled by a slider.
   ![uniform mode](images/uniform-screen.png)

   - **Music and animals Mode**: Allows control of the magnitude of specific musical instruments and animals sounds in a mixed signal.
   ![music and animals mode](images/music-and-animals-screen.png)

   - **Music and vowels mode**: Enables control of the magnitude of specific music instruments sounds and specific vowels from real life song.
   
   - **Wiener filter mode**: Enables the reduction of noise and enhancement of signal quality by optimally estimating the original signal from noisy observations.
    ![wiener mode](images/Wiener-screen.png) 
   

2. **Fourier Transform Visualization**:
   - Displays the Fourier transform of the input signal.
   - Allows switching between **linear scale** and **Audiogram scale** for frequency visualization.

3. **Linked Cine Signal Viewers**:
   - Synchronized viewers for input and output signals.
   - Full functionality, including play, stop, pause, speed control, zoom, pan, and reset.

4. **Spectrograms**:
   - Visual representation of the input and output signals' frequency content.
   - Automatically updates to reflect slider changes.
   - Option to toggle spectrogram visibility.

5. **Intuitive UI**:
   - Seamless switching between modes via menus or dropdowns.
   - Dynamically updated slider labels and functionality based on the selected mode.
     
   *Screenshot for UI*
   ![UI](images/general-screen.png)


## Usage

1. **Load a Signal**:
   - Open a WAV or other supported file format.

2. **Choose a Mode**:
   - Select one of the four available modes:
     - Uniform Range Mode
     - Music and Animals Mode

     - Music and vowels Mode
     - Wiener Filter Mode

3. **Adjust Sliders**:
   - Modify frequency components using sliders.
   - Observe real-time updates in the output spectrogram and signal viewer.

4. **Save Output**:
   - Save the modified signal as a new file.

## Notes

- Ensure proper slider-to-frequency mapping in non-uniform modes.
- The Fourier transform visualization is crucial for validating frequency manipulations.
- Synchronized cine viewers ensure an accurate time-domain representation.

#### **Demo**
https://github.com/user-attachments/assets/16b53a80-2f12-4857-a938-3e4309fe72b0


https://github.com/user-attachments/assets/aeaa6347-3590-4be8-91eb-2f46cb4c8c71


#### **Setup**
- Clone the repo
```bash
git clone https://github.com/Abdelrahman0Sayed/Signal-Equalizer.git
```
- Enter Project Folder
```bash
cd Signal-Equalizer
```
- Install the requirements
```bash
pip install -r requirements.txt
```

## Contributors <a name = "Contributors"></a>
<table>
  <tr>
    <td align="center">
    <a href="https://github.com/Abdelrahman0Sayed" target="_black">
    <img src="https://avatars.githubusercontent.com/u/113141265?v=4" width="150px;" alt="Abdelrahman Sayed Nasr"/>
    <br />
    <sub><b>Abdelrahman Sayed Nasr</b></sub></a>
    </td>
    <td align="center">
    <a href="https://github.com/MahmoudBL83" target="_black">
    <img src="https://avatars.githubusercontent.com/u/95527734?v=4" width="150px;" alt="Mahmoud Bahaa"/>
    <br />
    <sub><b>Mahmoud Bahaa</b></sub></a>
    </td>
    <td align="center">
    <a href="https://github.com/momowalid" target="_black">
    <img src="https://avatars.githubusercontent.com/u/127145133?v=4" width="150px;" alt="Mohamed Walid"/>
    <br />
    <sub><b>Mohamed Walid</b></sub></a>
    </td>
    <td align="center">
    <a href="https://github.com/Karim12Elbadwy" target="_black">
    <img src="https://avatars.githubusercontent.com/u/190773888?v=4" width="150px;" alt="Kareem El-Badawi"/>
    <br />
    <sub><b>Kareem El-Badawi</b></sub></a>
    </td>
    <td align="center">
    <a href="https://github.com/NadaMohamedElBasel" target="_black">
    <img src="https://avatars.githubusercontent.com/u/110432081?v=4" width="150px;" alt="Nada El-Basel"/>
    <br />
    <sub><b>Nada El-Basel</b></sub></a>
    </td>
      </tr>