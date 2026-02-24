# physics-playground

Real-time physics simulations using OpenGL/CUDA. 

## What I'm Implementing

### Physics Engine
- Rigid body dynamics (mass, velocity, acceleration)
- Collision detection (AABB, sphere-sphere, sphere-plane)
- Collision response (impulse-based resolution, restitution)
- Numerical integration (Euler, Verlet)
- Constraints and joints

### Simulations
- Falling boxes
- Bouncing balls
- Domino chain
- Wrecking ball
- Cloth simulation (Verlet integration)
- N-body gravity (galaxy simulation)

### GPU Acceleration (CUDA)
- Parallel collision detection
- Parallel integration
- 1000 particles (CPU) → 100,000+ particles (GPU)

## Dependencies
- [soft-raster](https://github.com/7vik03/software-raster) - My rendering engine

## Resources
- [Ten Minute Physics](https://www.youtube.com/c/TenMinutePhysics) - Matthias Müller's tutorials
- [Game Physics Engine Development](https://www.amazon.com/Game-Physics-Engine-Development-Commercial-Grade/dp/0123819768) - Ian Millington
- [Real-Time Collision Detection](https://www.amazon.com/Real-Time-Collision-Detection-Interactive-Technology/dp/1558607323) - Christer Ericson
