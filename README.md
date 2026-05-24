# haptixAR

**Developing systems to enable touch interfaces in extended reality environments.**

🌐 [haptixar.com](https://haptixar.com) · ✉️ info@haptixar.com

-

## What is haptixAR?

haptixAR is a patented system for enabling physical touch interaction in augmented and extended reality environments. It uses pattern recognition and occlusion detection to let users interact with virtual elements through direct physical contact - no controllers, no gloves, no additional sensors.

The core detection system is designed from the ground up for real-world deployment:

- **Low compute** - runs efficiently on resource-constrained devices
- **Low power** - suitable for battery-powered wearables and AR glasses
- **Low connectivity** - operates locally without cloud dependency
- **High stability** - reliable detection across variable lighting and environments

These properties make haptixAR a strong fit for both consumer AR applications and industrial environments where robustness, safety, and independence from network infrastructure are non-negotiable.

## Why haptixAR?

Current approaches to touch interaction in XR typically rely on hand tracking, depth sensors, or controller input. These methods introduce latency, power overhead, and points of failure that limit deployment in demanding environments.

haptixAR takes a fundamentally different approach. By detecting physical occlusion of known patterns, the system determines when and where a user has made contact with a surface. This makes touch detection a visual classification problem rather than a spatial estimation problem - resulting in a system that is simpler, faster, and more energy efficient than alternatives.

## Current Development

The first haptixAR implementation is underway: a financial trading simulation built in Unity for the Meta Quest 3, developed in collaboration with the University of Southampton's Winchester School of Art. This implementation uses OpenCV for Unity to drive the detection pipeline and serves as both a proof of concept and a foundation for benchmarking.

### Tech Stack

- Unity
- OpenCV for Unity
- Meta Quest 3 (passthrough AR)

## Repository Structure

This repository will grow to include:

- Reference implementations and integration examples
- Benchmarking tools and test harnesses
- Sample pattern assets for development and testing
- Documentation for building on the haptixAR detection system

## Intellectual Property

haptixAR is protected by a granted US patent (18/804,972) covering physical interaction with virtual environments through pattern recognition and occlusion detection. A corresponding German patent filing extends coverage into European markets.

The detection module is provided as a compiled library. Source-level access to the core detection system is not available.

## Get in Touch

If you are exploring touch interaction for AR/XR applications - whether consumer, industrial, or research - we'd like to hear from you.

- 🌐 [haptixar.com](https://haptixar.com)
- ✉️ info@haptixar.com

-

*haptixAR is developed by [BHB Technologies, Inc.](https://bhbtechnologies.com)*
