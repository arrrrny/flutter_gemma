## 0.10.1
- 🧠 **Thinking Mode**: Added thinking mode support for DeepSeek models with persistent thinking bubbles
- 🔧 **Function Call Fixes**: Fixed function calls detection in the middle of responses
- 💬 **UI Improvements**: Fixed loading indicator display after function calls
- 🔄 **JSON Response Handling**: Enhanced handling of JSON responses after function execution
- 📚 **Documentation**: Updated README with latest API changes and improved examples
- 🎨 **Code Quality**: Removed Russian comments and improved code consistency

## 0.10.0
- ✨ **Function Calling**: Added support for function calling, allowing models to interact with external tools.
- 🔧 **Improved Chat API**: Enhanced the chat API to support function calls and tool responses.

## 0.9.0
- 🖼️ **MULTIMODAL SUPPORT**: Added full support for text + image input with Gemma 3 Nano vision models
- 🎯 **Enhanced Message API**: New `Message` class with support for text, image, and multimodal content
    - `Message.text()` - for text-only messages
    - `Message.withImage()` - for text + image messages
    - `Message.imageOnly()` - for image-only messages
    - `message.hasImage` - to check if message contains image
- 📱 **Vision Models**: Full support for Gemma 3n E2B and E4B models with image understanding
- 🌐 **Web Platform**: Added graceful degradation with debug warnings for unsupported features

## 0.8.6
- 🚀 **GEMMA 3 NANO SUPPORT**: Added full support for Gemma 3 Nano models
- ⚡ Optimized session parameters for Gemma 3n models (temperature: 0.6, topK: 40, topP: 0.9)
- 🛡️ Added automatic fallback session creation for `input_pos != nullptr` errors
- 🎯 Added Gemma 3n model detection and compatibility handling
- 💪 Enhanced error handling for TensorFlow Lite model initialization
- 🔧 Fixed iOS session initialization with proper input position handling
- 📱 Improved mobile inference model with optimized parameters
## 0.8.5
- Upgraded Mediapipe to 0.10.24 for iOS and Android
- Added support of **Gemma3**, **Phi-4** and **DeepSeek** models for iOS
## 0.8.4
- iOS LoRA support added
- iOS topP support added
## 0.8.3
- Readme updated
## 0.8.2
- Readme updated
## 0.8.1
- Migrate to js-interop
- Add web platform support in pubspec.yaml
## 0.8.0
- Upgraded Mediapipe to 0.10.22 for Android and Web
- Upgraded Mediapipe to 0.10.21 for iOS
- Added opportunity to set *topP* and *preferredBackend* for inference
- Added support of **Gemma3**, **Phi-4** and **DeepSeek** models for Android and Web
## 0.7.0
- Added Chat functionality for instruction tuned model
- Added sizeInTokens method for analysis of the size of the input prompt
## 0.6.0
- Added opportunity to manage inference session
## 0.5.1
- Fixed crash on generation for Android
## 0.5.0
- IMPORTANT: Breaking changes in the API
- FlutterGemma instance was replaced with ModelManager and InferenceModel
- ModelManager to manage models and LoRA weights
- InferenceModel to manage inference
- Added opportunity to set model and LoRA weights paths manually
- Added opportunity to delete model and LoRA weights
- Added opportunity to load LoRA weights from assets and network
## 0.4.6
- Added close method
## 0.4.5
- Small fixes for Android
## 0.4.4
- Small fixes for iOS
## 0.4.3
- Upgraded Mediapipe to 0.10.20
- Updated LoRA support
## 0.4.2
- Added error handling
- Updated example for error handling
- Upgraded Mediapipe to 0.10.18 for iOS
- Fixed ios issue with model freezing
## 0.4.1
- Fixed ios issue
## 0.4.0
- Upgraded Mediapipe to 0.10.16
- Added LoRA support
- Fixed some issues
## 0.3.1
- Updated example and readme
## 0.3.0
- Added support for loading models from assets and network.
- Added progress updates for model loading.
## 0.2.4
- Fixed Mediapipe ios version
## 0.2.3
- Updated Mediapipe ios version
## 0.2.2
- Added opportunity to configure folder (Android only)
- Fixed android release issue
- Updated Mediapipe for Android
- Updated readme
## 0.2.1
- Updated chat functionality for instruction tuned model
- Updated readme
## 0.2.0
- Added chat functionality for instruction tuned model
- Updated example
## 0.1.4
- Updated readme for GPU models on Android devices
- Updated example
## 0.1.3
- Updated readme
## 0.1.2
- Updated example
## 0.1.1
- Updated example
## 0.1.0
- Added web support
- Added opportunity to set *randomSeed*, *topK* and temperature
## 0.0.4
- Updated example
- Updated readme
## 0.0.3
- Added getResponseAsync method
## 0.0.2
- Added description in Readme.md
- Added opportunity to setup a model before initiation
## 0.0.1
- Initial release
































