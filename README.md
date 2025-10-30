## Underground Spotify Discovery (WIP)

🚧 **This project is in active development - nothing works yet, but the vision is clear!** 🚧

**We analyze Spotify to find you unknown artists in the styles you love.**

Think of us as your personal music scout: digging through Spotify's catalog to surface hidden gems that match your taste perfectly, but that algorithms would never show you.

This platform aims to uncover artists who fly completely under the radar: because great music isn't always backed by great marketing. 

We believe that talent deserves to be heard, regardless of an artist's promotional skills, geographic location, or background. Our goal is to level the playing field, giving every creator a fair chance to find their audience.

**Great music shouldn't be a privilege of those who can promote it best.**


## What does it do (well not yet) ?

We leverage Spotify's API to:
- **Discover** artists with limited exposure
- **Curate** personalized playlists showcasing hidden gems
- **Connect** with your next favorite artist
- **Support** the growth of independent music scenes

### Backend
- **Python** with Spotipy library
- **Spotify Web API** integration
- **Environment variables** for secure configuration

### Frontend  
- **HTML5** with Tailwind CSS
- **Vanilla JavaScript**
- **Spotify Embed Player**

## Current Development Focus

We're actively working on solving these core challenges to build a better discovery platform:

### Algorithm & Fairness
- **How to prevent frequently-posting artists from dominating recommendations?**
  - Exploring time-weighted algorithms and rotation systems
  - Balancing recency against artist saturation
- **Creating meaningful artist bios automatically**
  - Generating contextual descriptions from musical data
  - Combining genre, influence, and musical characteristics

### Interface & Experience  
- **Building a modern web interface for music discovery**
  - Real-time filtering and exploration capabilities
  - Visual artist relationships and genre mapping
- **Integrating artist profile pictures in the player**
  - Dynamic loading from multiple sources
  - Fallback strategies for missing images

### Advanced Discovery Strategies
I'm developing multi-layered search approaches to find artists invisible to standard APIs:

**Current Strategy Stack:**
- **Genre-based discovery** (metalcore, deathcore, djent, etc.)
- **Temporal filtering** (2025 releases, October 2025 focus)
- **Combination searches** (genre + year + popularity thresholds)
- **Cross-referencing** with external databases for completeness

### API Limitations
**Major hurdles we're tackling:**
- **Regional restrictions blocking artist access** (particularly affecting French users)
- **Country-specific new releases** instead of global underground scenes
- **No direct API support** for "recently created artists" or "low-popularity new releases"
- **Geographic filtering** that hides emerging artists from international audiences

**Our approach:**
- Multi-region API queries to bypass geographic blocks
- External data source integration to complement Spotify's limitations
- Community-sourced artist submissions to fill discovery gaps
- Advanced filtering that works within (and around) API constraints

### Technical Exploration
- **Building proxy services** to access region-locked content
- **Implementing fair rotation systems** to ensure diverse artist exposure
