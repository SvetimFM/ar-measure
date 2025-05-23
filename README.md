# MeasureAR - Mixed Reality Measurement Tool

A powerful AR measurement application optimized for iOS devices using WebXR and ARKit features.

## Features

### Core Measurement Tools
- **Distance Measurement**: Tap two points to measure distances in real space
- **Angle Measurement**: Measure angles between three points
- **Area Calculation**: Create polygons and calculate surface areas
- **Level Tool**: Use device orientation to check if surfaces are level

### iOS AR Kit Integration
- **WebXR Support**: Native AR capabilities through Safari
- **LiDAR Support**: Automatic detection and utilization of LiDAR scanner on iPhone 12 Pro and newer
- **Depth Sensing**: Real-world depth perception for accurate measurements
- **Plane Detection**: Automatic detection of surfaces for better measurement accuracy
- **Hit Testing**: Place measurement points accurately on detected surfaces

### Optimizations for iOS
- Full-screen web app support
- Haptic feedback on measurements
- Camera optimizations for iOS devices
- Motion sensor integration
- Portrait and landscape orientation support

## Device Compatibility

### Fully Supported (with AR)
- iPhone 12 Pro / Pro Max (LiDAR)
- iPhone 13 Pro / Pro Max (LiDAR)
- iPhone 14 Pro / Pro Max (LiDAR)
- iPhone 15 Pro / Pro Max (LiDAR)
- iPad Pro 2020 and later (LiDAR)

### Supported (Camera-based measurements)
- All iPhones with iOS 11+
- All iPads with iOS 11+

## Usage

1. Open the app in Safari on your iOS device
2. Allow camera permissions when prompted
3. For AR mode:
   - Tap "Start AR" button (if available)
   - Move device to detect surfaces
   - Tap to place measurement points
4. For camera mode:
   - Point camera at objects
   - Tap screen to add measurement points

## Technical Implementation

- **WebXR API**: For AR session management
- **Three.js**: 3D rendering and visualization
- **ARKit Features**: Accessed through WebXR
- **Progressive Web App**: Installable on home screen
- **Responsive Design**: Adapts to all iOS screen sizes

## Privacy

- All measurements are processed locally on device
- No data is sent to servers
- Camera access is required only for measurements
- Motion sensor data stays on device

## Development

Built with modern web technologies:
- HTML5 Canvas for rendering
- WebXR API for AR capabilities
- Three.js for 3D graphics
- Native iOS optimizations

The app automatically detects device capabilities and enables features accordingly.