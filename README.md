# Voxel51_VisualAI_Hackathon
# Project Title - Endangered Sea Animals
## Contributors - Angel Fernandes​, Ankesh Kumar​, Jason Leung​, Jian Gao

## Objective - Detecting each of 5 endangered species as well as classifying underwater photos as containing an endangered animal versus containing ~20 non-endangered species. 

Dataset Preperation - Sea Animals Image Dataset (https://www.kaggle.com/datasets/vencerlanz09/sea-animals-image-dataste)
- 23 different Sea animal classes.
class_1: ['Sea Urchins', 'Puffers', 'Rays', 'Eels', 'Sea Otter']
class_0: ['Turtle_Tortoise', 'Jelly Fish', 'Dolphin', 'Sharks', 'Whale', 'Octopus', 'Sea Rays', 'Nudibranchs', 'Otter', 'Corals', 'Crabs', 'Starfish', 'Lobster', 'Clams', 'Eel', 'Fish', 'Shrimp', 'Squid', 'Penguin', 'Seahorse', 'Seal']


## Model for Classification 
- Transfer Learning (Using ResNet50 trained with new Last Layer)
- Optimized on Loss function to improve over-fitting

## Results - 
- Epoch: 0, Train Loss: 0.4005, Validation Loss: 0.2359
- Epoch: 1, Train Loss: 0.1550, Validation Loss: 0.1864
- Epoch: 2, Train Loss: 0.0602, Validation Loss: 0.1983
- Epoch: 3, Train Loss: 0.0277, Validation Loss: 0.2220
- Epoch: 4, Train Loss: 0.0161, Validation Loss: 0.2447
### Test Accuracy: 0.9452

<img width="432" alt="image" src="https://github.com/user-attachments/assets/55c815a1-7d95-4614-a1dc-904d4ebe50a1">

Powerpoint presentation attached that our hackathon group presented to the whole gathering at the end of a full day of hacking! We weren't able to quite get the ResNet results by the 3:30pm deadline to be able to show in our powerpoint but we got some decent results an hour later, just too late to present! I think we have a pretty beneficial use case here for image classification that would be useful for underwater camera trap systems.
