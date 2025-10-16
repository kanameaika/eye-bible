# System structure

## WASM Module 1: Face Mesh

Inspired by WebGazer.js (see https://github.com/brownhci/WebGazer), a Face Mesh based on Tensorflow is employed to extract eye region boundaries.

## WASM Module 2: Gaze

Based on C/C++ algorithms compiled to WebAssembly, low error gaze positions coordinates are delivered.

## Js: Page Turning

Based on he gaze coordinates (x, y) and confidence values, the system triggers page turning operations.

The code can be used only with your laptop camera in a web browser environment.
