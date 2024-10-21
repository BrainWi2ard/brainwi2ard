# BrainWi2ard

BrainWi2ard is a user-friendly GUI software that integrates features from multiple deep learning projects to create a comprehensive tool for real-time voice cloning, deepfake video generation, and lip-syncing. This software is compatible with macOS, Linux, and Windows.

## Features
- **Real-Time Voice Cloning**: Clone a voice in 5 seconds to generate arbitrary speech in real-time.
- **Deepfake Video Generation**: Create deepfake videos using pre-trained models or train your own.
- **Lip-Syncing**: Accurately lip-sync videos in any language.

## Installation
### Prerequisites
- Python 3.7+
- ffmpeg
- PyTorch

### Installation Steps
1. **Clone the Repositories**:
    ```bash
    git clone https://github.com/iperov/DeepFaceLive.git
    git clone https://github.com/CorentinJ/Real-Time-Voice-Cloning.git
    git clone https://github.com/snehitvaddi/Deepfake-using-Wave2Lip.git
    git clone https://github.com/hectorgie/DeepFaceLab.git
    ```

2. **Install Requirements**:
    ```bash
    cd DeepFaceLive
    pip install -r requirements.txt
    cd ../Real-Time-Voice-Cloning
    pip install -r requirements.txt
    cd ../Deepfake-using-Wave2Lip
    pip install -r requirements.txt
    cd ../DeepFaceLab
    pip install -r requirements.txt
    ```

3. **Download Pre-trained Models** (if applicable):
    - Follow the instructions in each repository to download and set up pre-trained models.

4. **Run the GUI**:
    - Implement a unified GUI using a framework like PyQt or Tkinter, integrating features from all repositories.

## Usage
### Real-Time Voice Cloning
1. Navigate to the Real-Time-Voice-Cloning directory:
    ```bash
    cd Real-Time-Voice-Cloning
    ```
2. Run the toolbox:
    ```bash
    python demo_toolbox.py -d <datasets_root>
    ```

### Deepfake Video Generation
1. Follow the instructions in the DeepFaceLab repository to create and train deepfake models.
2. Use DeepFaceLive to apply real-time face swaps during video calls or streams.

### Lip-Syncing
1. Navigate to the Deepfake-using-Wave2Lip directory:
    ```bash
    cd Deepfake-using-Wave2Lip
    ```
2. Run the lip-sync script with your base video and audio file:
    ```bash
    python inference.py --checkpoint_path <path_to_checkpoint> --face <path_to_video> --audio <path_to_audio>
    ```

## Contributing
Contributions are welcome! Please fork this repository and submit pull requests.

## License
This project is licensed under the MIT License.


-->
