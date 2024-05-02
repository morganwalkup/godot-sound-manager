# Sound Manager

A Godot plugin for simplifying audio players.

Creates a globally-accessible `SoundManager` singleton that plays audio streams using a rotating pool of audio players.

```
var music = preload("res://my_music.ogg")
var sound_effect = preload("res://my_sound_effect.wav")
var ui_sound_effect = preload("res://my_ui_sound_effect.wav")

SoundManager.play_music(music, 2.0)
SoundManager.play_sound(sound_effect)
SoundManager.play_sound(ui_sound_effect)
```

See `sound_manager.gd` for public methods