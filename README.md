# 600 Billboard Hot 100 Tracks (with Spotify Data)

This project provides a comprehensive glimpse into the evolution of contemporary music, featuring **620 tracks** from **87 artists** who dominated the charts between 2000 and 2023. Representing the pulse of modern pop and R&B, this dataset captures the diversity and dynamism of the Billboard Hot 100 hits over the past two decades.

Each track is meticulously annotated with Spotify's audio features, offering a rich, data-driven perspective on the sonic characteristics that have shaped 21st-century music. Key features include tempo, energy, danceability, and valence, making this dataset a valuable resource for exploring the trends and transformations in popular music.

## Dataset Overview

The dataset includes the following key columns:

- **Track Name**: The name of the song  
- **Artist**: The performer of the track  
- **Release Year**: The year the song was released  
- **Spotify Audio Features**:
  - **Tempo**: Beats per minute (BPM)  
  - **Energy**: Intensity and activity level of the track  
  - **Danceability**: Suitability for dancing  
  - **Valence**: Positivity of the track's mood  
  - **Loudness**: Volume level in decibels (dB)  
  - **Acousticness**: Likelihood of the track being acoustic  
  - **Speechiness**: Presence of spoken words in the track  

## Project Structure

- **Data Loading**: The dataset is accessed via Google Drive or manual upload.  
- **Libraries Used**:
  - `pandas` for data manipulation  
  - `numpy` for numerical operations  
  - `plotly` and `seaborn` for interactive and static visualizations  
  - `scipy` for statistical analysis  
  - `sklearn` for data preprocessing  

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/brunoribeirol/billboard-hot-tracks.git
   cd billboard-hot-tracks
  
2. Run the notebook locally:
- Ensure you have Jupyter Notebook or Jupyter Lab installed.
- Install required dependencies:
  ```bash
  pip install pandas numpy plotly matplotlib seaborn scipy scikit-learn
  ```
- Launch the notebook:
  ```bash
   jupyter notebook 600_billboard_hot_100_tracks.ipynb
  ```
    
## Analysis Highlights
- **Trends in Tempo and Energy**: Explore how the tempo and energy of Billboard hits have evolved over the years.
- **Danceability and Valence**: Analyze how danceability and mood (valence) vary across different eras of popular music.
- **Top Artists and Tracks**: Identify which artists dominated the charts and how their music characteristics compare.
- **Genre Evolution**: Discover trends in music genres and styles over the past two decades.


## Contributing
Contributions are welcome! Please follow these steps to contribute:
1. Fork the repository.
2. Create a new branch (git checkout -b feature/YourFeatureName).
3. Commit your changes (git commit -m 'Add some feature').
4. Push to the branch (git push origin feature/YourFeatureName).
5. Open a pull request.
   
## License
This project is licensed under the MIT License.
