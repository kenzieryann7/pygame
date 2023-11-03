Mac Installation
============================

How to install with dependencies on Mac OS with Homebrew

1. Install the SDL dependencies
brew install sdl2 sdl2_image sdl2_mixer sdl2_ttf pkg-config

2. Install XQuartz (Optional)
brew install Caskroom/cask/xquartz

3. Install portmidi (Optional)
brew install portmidi

4. Install latest Pygame from source
python3 -m pip install git+https://github.com/pygame/pygame.git

5. Verify all Pygame tests
python3 -m pygame.tests
