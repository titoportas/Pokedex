## Compose App Size
All sizes are from debug application:
1. Initial .apk size:

6.8 MB

2. After setting up compose and adding the following libraries:
// compose
implementation "androidx.compose.ui:ui:$versions.compose"
// Tooling support (Previews, etc.)
implementation "androidx.compose.ui:ui-tooling:$versions.compose"
// Foundation (Border, Background, Box, Image, Scroll, shapes, animations, etc.)
implementation "androidx.compose.foundation:foundation:$versions.composeFoundation"
// Material Design
implementation "androidx.compose.material:material:$versions.compose"

9.4 MB (+2.6 MB)