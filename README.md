# Personal Spotify Visualizer Web App

## Overview
This custom application leverages the Spotify API to fetch detailed information about tracks, focusing on metrics like beats per minute, loudness, and energy. It translates these attributes into dynamic, colorful visualizations, offering a unique, interactive music experience.

## How it Works
Spotify's extensive data analysis of user habits and music attributes allows this app to create engaging visualizers for specific tracks. By tapping into audio features provided by Spotify, the app crafts visual representations that mirror the music's energy and mood.

### Audio Features
The app utilizes Spotify's audio features, which quantify the subjective listening experience of tracks, converting aspects like mood and tempo into numerical values. These values help predict user preferences and are central to the visualizer's functionality.

### Visualizer Categories
The visualizer categorizes songs into four groups based on their valence and energy levels, each with unique visual elements:

#### Dance Floor
- **Criteria:** Energy > 0.750, Valence > 0.500
- **Behavior:** Fast color changes with danceability, brighter colors for higher valence, more tiles with quicker tempo.
- **Example Tracks:** "24K Magic" by Bruno Mars, "Don't Start Now" by Dua Lipa.

#### Energy Source
- **Criteria:** Energy < 0.750, Valence > 0.500
- **Behavior:** Brighter source with more energy, faster color change with danceability, quicker pulsing with higher tempo.
- **Example Tracks:** "Waiting" by Deniece Williams, "The Less I Know The Better" by Tame Impala.

#### Spinning Orbs
- **Criteria:** Energy > 0.500, Valence < 0.500
- **Behavior:** Larger orbs for more energy, faster expansion/contraction with danceability, brighter and faster pendulations with higher valence and tempo.
- **Example Tracks:** "Under Your Spell" by Desire, "The Chain" by Fleetwood Mac.

#### Floating Bubbles
- **Criteria:** Energy < 0.500, Valence < 0.500
- **Behavior:** Brighter bubble outlines with more energy, colorful bubbles with danceability, larger bubbles and more bubbles with higher valence and tempo.
- **Example Tracks:** "Something About Us" by Daft Punk, "The Void" by Kid Cudi.

## How to Use
Access the app, connect your Spotify account, select a track, and watch as the visualizer transforms the song's attributes into a vibrant visual experience.

### Customization
Users can interact with the visualizer to adjust aspects like color intensity, bubble size, or the speed of the visual elements to match personal preferences or explore how different tracks influence the visual output.

## Conclusion
The Personal Spotify Visualizer Web App is a fascinating tool that bridges the gap between music and visual art, offering a personalized experience that enhances the enjoyment of Spotify tracks through captivating visual representations.
