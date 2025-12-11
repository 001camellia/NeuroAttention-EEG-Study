# 🧠 NeuroAttention-EEG-Study: EEG-based Attention Mechanism Research in UI Interface Design

## 📋 Project Overview
This study combines neuroscience and user interface design to analyze the impact of different mobile interface designs on users' neural attention mechanisms using EEG signals. By analyzing EEG responses to dynamic icons at different positions, we aim to validate and deepen the neuroscientific foundation of UI design principles.
## 🎓 Research Team & Affiliation
- **Research Team**: Neuro-Interface Interaction Group
- **Institution**: Hangzhou Dianzi University
- **Research Members**: Chen Xu, Li Yan, Feng Ying, Hu Binwei, Zhu Li

## 🎯 Research Objectives
- **Validate the neural basis of UI design principles**: Provide neuroscientific evidence for existing design principles
- **Compare neural response differences**: Analyze brain responses to dynamic icons at different interface positions
- **Evaluate layout organization methods**: Compare attention allocation patterns between vertical and horizontal layouts
- **Investigate temporal dynamic characteristics**: Analyze the time-varying features of neural perception
- **Integrate multimodal data**: Combine EEG and eye-tracking data for comprehensive analysis of attention mechanisms

## 🔬 Research Background
### Existing UI Design Principles
Previous research has shown:
- **Left-positioned icons** attract more user attention compared to right-positioned icons
- **Bottom-positioned icons** are more effective at capturing user attention compared to top-positioned icons

### Current Study Design
- **Number of participants**: 9 healthy volunteers
- **Data modalities**: Synchronously recorded EEG + eye-tracking data
- **Interface conditions**: Mobile interfaces with/without dynamic icons
- **Layout variations**: Vertical and horizontal divisions of Areas of Interest (AOIs)

## 📊 Experimental Conditions and Comparisons
### Five Comparative Analysis Modules:

1. **Dynamic Icons Presence Comparison**
   - Condition A: Interface containing dynamic icons
   - Condition B: Interface without dynamic icons
   - Analysis focus: Differences in neural activation and visual attention

2. **Layout Organization Comparison**
   - **Vertical division**: Icons arranged in vertical columns
   - **Horizontal division**: Icons arranged in horizontal rows
   - Analysis focus: Spatial patterns of attention distribution

3. **Temporal Dynamic Effects Analysis**
   - Stimuli with different presentation durations
   - Analysis focus: Temporal characteristics of neural adaptation

4. **Position Effect Validation**
   - Top vs. bottom placement
   - Left vs. right placement
   - Purpose: Validate the neural basis of traditional design principles

5. **Multimodal Correlation Analysis**
   - EEG metrics vs. eye-tracking metrics
   - Neural activation vs. visual fixation patterns

## 🧬 EEG Analysis Pipeline
### 1. Data Acquisition and Preprocessing
- **Equipment**: 64-channel EEG system
- **Sampling rate**: 1000 Hz
- **Preprocessing pipeline**:
  - Band-pass filtering: 0.5-45 Hz
  - Bad channel detection and interpolation
  - ICA-based artifact removal
  - Average re-referencing

### 2. Feature Extraction Metrics
- **Power Spectral Density (PSD)**: Calculation of power in each frequency band
  - Delta waves (1-4 Hz)
  - Theta waves (4-8 Hz)
  - Alpha waves (8-13 Hz)
  - Beta waves (13-30 Hz)
  - Gamma waves (30-45 Hz)
- **Permutation Entropy**: Signal complexity analysis
- **Event-Related Potentials (ERPs)**: Time-domain dynamic features
- **Functional Connectivity**: Coordination between brain regions

### 3. Brain Topographic Map Visualization
- **Topographic maps for each frequency band**: Display spatial distribution of neural activation
- **Statistical parametric maps**: Group-level significance testing
