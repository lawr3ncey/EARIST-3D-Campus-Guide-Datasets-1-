# EARIST-3D-Campus-Guide-Datasets-1-

Datasets for the EARIST Cavite Adaptive 3D Campus Guide Thesis Project.

This repository contains essential data used for the development of the system, including predefined phrases and campus room names that serve as the basis for voice recognition, navigation, and pathfinding.

---

## Datasets Description

### 1. `phrases.json`
This file contains a list of test phrases used to evaluate the system's natural language processing (NLP) capabilities. Each phrase includes a placeholder (`[location]`) that represents a specific destination within the campus. These phrases simulate user voice commands for navigation.

#### Purpose:
- Used for testing and validating the voice command recognition module.
- Ensures the system can interpret and respond to various command structures.

#### Sample Data:
```json
{
  "testPhrases": [
    "How to get to [location]",
    "Where is [location]",
    "Show me the way to [location]",
    "Find [location]",
    "Take me to [location]",
    "Navigate [location]"
  ]
}
