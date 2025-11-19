# Moel Inversion Attack Simulation

Imagine a bank's IVR system uses your unique voiceprint (like a fingerprint, but for your voice) to authenticate you.

The Model Inversion Attack doesn't steal the bank's database; it targets the AI brain that was trained to recognize your voice. This AI brain, after being trained, inadvertently keeps a high-resolution "picture" of your voiceprint in its memory.

The attack works by showing the AI random noise and telling it, "Make this noise sound like User ID 999." Using mathematical feedback, the noise is slowly sculpted, pixel-by-pixel, until it perfectly matches the unique vocal characteristics of User ID 999.

The result is a cloned voice feature vector that can be turned into a playable audio file to impersonate the victim and bypass security.
