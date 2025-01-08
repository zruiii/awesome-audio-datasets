# awesome-audio-datasets
🎵 A curated collection of open-source audio datasets for Speech and Music.

This repository aims to provide researchers and developers with comprehensive information about publicly available audio datasets, focusing on their size, language coverage, collection methods, and intended use cases. Each dataset is accompanied by detailed descriptions and statistical information to help you choose the right dataset for your specific needs.

## Quick Reference Table

| Dataset         | Lang.             | Data Source  | Hours    | Primary Use Cases |
| --------------- | ----------------- | ------------ | -------- | ---------------- |
| Common Voice    | Multilingual      | In-the-wild  | Varies   | ASR              |
| LJSpeech        | En                | Recording    | 24       | TTS              |
| LibriSpeech     | En                | Recording    | 1,000    | ASR              |
| LibriTTS        | En                | Recording    | 584      | TTS              |
| Libri-Light     | En                | Recording    | 60,000+  | ASR              |
| GigaSpeech      | En                | In-the-wild  | 10,000   | ASR              |
| VCTK            | En                | Recording    | 44       | TTS              |
| VoxCeleb        | En                | In-the-wild  | 2,000+   | Speaker Recognition |
| WenetSpeech4TTS | Zh                | In-the-wild  | 12,483   | TTS              |
| Aishell        | Zh                | Recording    | 1,000    | ASR              |
| Emilia          | En/Zh/De/Fr/Ja/Ko | In-the-wild  | 101,653  | TTS              |

## Detailed Dataset Information

### [Common Voice](https://commonvoice.mozilla.org/en/datasets)
**Release Date**: 2017 (continuously updated)  
**Primary Use**: Automatic Speech Recognition (ASR)  
**Description**: An open-source speech dataset initiative by Mozilla supporting multiple languages. The data comes from global volunteer contributions and includes rich speaker metadata including age, gender, and accent information.  
**Distribution**: Varies by version and language.

### [LJSpeech](https://keithito.com/LJ-Speech-Dataset/)
**Release Date**: 2017  
**Primary Use**: Text-to-Speech (TTS)  
**Description**: A single female speaker English speech dataset with high-quality, professional studio recordings.  
**Distribution**: 24 hours total, containing 13,100 audio clips.

### [LibriSpeech](https://www.openslr.org/12)
**Release Date**: 2015  
**Primary Use**: ASR  
**Description**: Derived from LibriVox audiobooks, comprising approximately 1,000 hours of English reading speech.  
**Distribution**: Multiple splits available for different use cases.

### [LibriTTS](https://www.openslr.org/60)
**Release Date**: 2019  
**Primary Use**: TTS  
**Description**: A reprocessed version of LibriSpeech materials specifically designed for speech synthesis tasks.  
**Distribution**: Approximately 584 hours of English speech.

### [Libri-Light](https://github.com/facebookresearch/libri-light/blob/main/data_preparation/README.md)
**Release Date**: 2019  
**Primary Use**: ASR  
**Description**: A large-scale unlabeled speech dataset based on LibriVox.  
**Distribution**:
| Subset  | Hours   |
|---------|---------|
| small   | 577h    |
| medium  | 5,193h  |
| large   | 51,934h |

### [VCTK](https://datashare.ed.ac.uk/handle/10283/3443)
**Release Date**: 2019  
**Primary Use**: TTS  
**Description**: Audio recordings from 100 English speakers with various accents, each reading approximately 400 sentences.

### [GigaSpeech](https://github.com/SpeechColab/GigaSpeech)
**Release Date**: 2021  
**Primary Use**: ASR  
**Description**: Large-scale English speech dataset collected from podcasts, YouTube, and audiobooks.  
**Distribution**:
| Subset | Audiobook | Podcast | YouTube | Total   |
|--------|-----------|----------|----------|---------|
| XL     | 2,655h    | 3,499h   | 3,846h   | 10,000h |
| L      | 650h      | 875h     | 975h     | 2,500h  |
| M      | 260h      | 350h     | 390h     | 1,000h  |
| S      | 65h       | 87.5h    | 97.5h    | 250h    |
| XS     | 2.6h      | 3.5h     | 3.9h     | 10h     |

### VoxCeleb
**Release Date**: 2017 ([VoxCeleb1](https://www.robots.ox.ac.uk/%7Evgg/data/voxceleb/vox1.html)), 2018 ([VoxCeleb2](https://www.robots.ox.ac.uk/~vgg/data/voxceleb/vox2.html))  
**Primary Use**: Speaker Recognition and Verification  
**Description**: Large-scale speaker datasets extracted from YouTube videos, featuring speech in various real-world environments.  
**Distribution**:
| Version    | Hours | Speakers | Segments  |
|------------|-------|----------|-----------|
| VoxCeleb1  | 352   | 1,251    | 153,516   |
| VoxCeleb2  | 2,442 | 6,112    | 1,128,246 |

### [WenetSpeech4TTS](https://modelscope.cn/datasets/dukguo/WenetSpeech4TTS)
**Release Date**: 2024  
**Primary Use**: TTS  
**Description**: Extended from WenetSpeech dataset, focused on addressing noise, distortion, and semantic completeness issues.  
**Distribution**:
| Training Subsets | DNSMOS Threshold | Hours | Avg. Duration (s) |
|------------------|------------------|-------|-------------------|
| Premium          | 4.0              | 945   | 8.3              |
| Standard         | 3.8              | 4056  | 7.5              |
| Basic            | 3.6              | 7226  | 6.6              |
| Rest             | <3.6             | 5574  | N/A              |

### [Aishell Series](https://www.aishelltech.com/kysjcp)
#### Aishell-1
**Release Date**: 2017  
**Primary Use**: ASR  
**Description**: 178 hours of audio recorded by 400 speakers from different regions of China, covering 11 domains including smart home, autonomous driving, and industrial production.

#### Aishell-2
**Release Date**: 2018  
**Primary Use**: ASR  
**Description**: 1,000 hours of audio recorded by 1,991 speakers, covering 12 domains including wake words, voice control, smart home, autonomous driving, and industrial production.

#### Aishell-3
**Release Date**: 2020  
**Primary Use**: TTS  
**Description**: 85 hours of high-fidelity audio recorded by 218 speakers in a quiet indoor environment.

### [Emilia](https://modelscope.cn/datasets/modelscope/Emilia-Dataset)
**Primary Use**: TTS  
**Description**: A large-scale multilingual dataset primarily focused on English and Chinese, with additional coverage of German, French, Japanese, and Korean.  
**Distribution**:
| Language  | Duration (hours) |
|-----------|-----------------|
| English   | 46,828          |
| Chinese   | 49,922          |
| German    | 1,590           |
| French    | 1,381           |
| Japanese  | 1,715           |
| Korean    | 217             |

## Contributing
Feel free to submit pull requests to add new datasets or update existing information. Please ensure that any added dataset is publicly available and includes detailed information about its contents and usage rights.
