# flower-finder

## datasets
- https://universe.roboflow.com/my-stuff-0wmth/flowerdetecter-v2/dataset/1
- https://worldfloraonline.org/classification
- https://www.kaggle.com/datasets/abhayayare/flower-dataset/data
- https://www.kaggle.com/datasets/aksha05/flower-image-dataset
- https://www.kaggle.com/datasets/kausthubkannan/5-flower-types-classification-dataset
- https://www.kaggle.com/datasets/nunenuh/pytorch-challange-flower-dataset
- https://www.tensorflow.org/datasets/catalog/i_naturalist2021

## tutorials
- https://www.youtube.com/watch?v=h6TJiGrYINk
- https://www.youtube.com/watch?v=Hr06nSA-qww

## to-do
-[] 

## flower id + visualization

### project overview
*A comprehensive machine learning application that enables users to:*
1. Capture or upload a flower image
2. Automatically identify the flower's common and scientific names
3. Generate a 3D model representation of the flower
4. Create a pixelated font/icon of the identified flower

*Technical Components*
1. Image Recognition Model
  - Architecture**: Convolutional Neural Network (CNN)
  - Base Model: ResNet50 or EfficientNet
  - Transfer Learning from pre-trained botanical datasets
  - High-accuracy flower species classification
2. Training Data Requirements:
    - Comprehensive flower image dataset
    - Minimum 100 images per flower species
    - Diverse angles, lighting conditions, and backgrounds
    - Sources:
        - iNaturalist
        - PlantNet
        - Custom augmented datasets
3. Classification Metrics:
    - Accuracy Target: >95%
    - Top-3 Species Confidence
    - Probabilistic species matching
3. Flower Database Integration  
    *Database Contents*:
    - Scientific name
    - Common name(s)
    - Botanical family
    - Native region
    - Bloom season
    - Additional metadata
4. 3D Model Generation
    *Techniques* 
    - Photogrammetry-based reconstruction
    - Procedural 3D modeling
    - Machine learning-assisted shape generation
    **Output Specifications** 
    - Formats: .OBJ, .GLTF, .FBX
    - Low-poly and high-poly variants
    - Texture mapping
    - Color accuracy matching original image
5. Pixelated Font/Icon Generation
    - Generation Methods
        - Automated pixel art conversion
        - Color palette extraction from original image
        - Adaptive resolution scaling
        - Preservation of flower's key structural elements
    - Output Specifications
        - Multiple sizes (16x16, 32x32, 64x64 pixels)
        - Transparent background
        - Color fidelity to original flower

### Technology Stack
- Backend: Python
- ML Frameworks: TensorFlow, PyTorch
- 3D Modeling: Blender API
- Web Framework: Flask/FastAPI
- Frontend: React/Vue.js
- Mobile: React Native/Flutter

### Ethical Considerations
- Respect botanical research intellectual property
- Ensure accurate scientific representation
- Provide educational context with identification

### Potential Applications
- Botanical research
- Educational tools
- Gardening applications
- Nature photography assistants
- Ecological biodiversity tracking

### Development Roadmap

1. Dataset Compilation (3 months)
2. ML Model Training (4 months)
3. 3D/Pixel Generation Algorithms (3 months)
4. Integration & User Interface (2 months)
5. Testing & Refinement (3 months)

### Estimated Resources
- Computational Resources: High-performance GPU cluster
- Storage: 10+ TB for datasets
- Team:
    - 2 Machine Learning Engineers
    - 1 3D Modeling Specialist
    - 1 Frontend Developer
    - 1 Database Architect
