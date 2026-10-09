## 1. PEAS Framework & Environment Characteristics
#### A. PEAS Framework for the Self-Driving Trailer Agent
- Performance Measures: Safety (zero collisions and road infractions). Trip duration and whether delivery deadlines are met. Fuel efficiency and minimizing the total distance travelled. Cargo safety, including avoiding sudden braking and maintaining stable movement during transportation.

- Environment: Kenya’s highway network, including the A104, B1, B3, and A1 corridors. Different road conditions, road construction areas, speed bumps, potholes, and changes in terrain such as the Rift Valley escarpments. Other road users, including heavy trucks, matatus, passenger vehicles, motorcycles (boda-bodas), pedestrians, and wandering livestock. Weather conditions such as heavy rain and fog, especially around areas such as Limuru and Mau Summit.

- Actuators: Electronic throttle/accelerator control. Air-braking system and retarder. Steering mechanisms for controlling the steering angle. Transmission and gear selection. Signalling and lighting systems, including turn indicators, headlights, brake lights, and hazard lights.

- Sensors: Long-range LiDAR and radar for detecting obstacles and supporting adaptive cruise control. Cameras for detecting lanes, road signs, traffic lights, and pedestrians. GPS/GNSS and an IMU (Inertial Measurement Unit) for determining the vehicle’s position and orientation. Wheel-speed sensors and engine diagnostics for monitoring vehicle speed, fuel level, tyre pressure, and other vehicle conditions.

#### B. Environment Dimensions
### B. Environment Dimensions

* **Partially Observable vs. Fully Observable:** **Partially Observable.** The trailer agent cannot know everything happening on the road at a given time. It may not know about traffic jams ahead, broken-down vehicles or sudden changes in weather around areas like Mau Summit.

* **Deterministic vs. Stochastic:** **Stochastic.** Road and traffic conditions can change unexpectedly. Other drivers may behave unpredictably, pedestrians may cross the road suddenly and weather conditions may change, making it difficult to predict the exact outcome of an action.

* **Episodic vs. Sequential:** **Sequential.** Each decision affects what happens next. For example, choosing a route through the A104 instead of the B3 via Narok affects the distance travelled, fuel consumption and the route options available later.

* **Static vs. Dynamic:** **Dynamic.** The road environment changes while the agent is making decisions. Traffic levels, the positions of other vehicles and road conditions can change at any time.

* **Discrete vs. Continuous:** **Continuous.** The trailer's speed, position, steering angle and distance travelled can take different values within a range. However, when planning routes, road junctions can be represented as discrete points on a map.

## 2. Directed Graph & Search Tree (with Abstraction)
#### A. Directed Graph of Candidate Road Networks
#### B. Search Tree (Applying Abstraction)


## 3. Path Cost Function & Optimal Path Determination
#### A. Distance Breakdown by Road Segment
#### B. Route Path Cost Evaluation
#### C. Optimal Path Conclusion


## 4. Group Work Evidence
### Meeting Minutes
- **Date**: 07/10/2026
- **Platform**: Google Meet
- **Members Present**: Albert Miricho, Sean Nguyo, Sydney Aisha
- **Agenda**:
  1. Problem formulation and PEAS definition.
  2. Construction of a highway-directed graph and abstraction tree.
  3. Distance verification on Google Maps.
  4. Repository fork verification and Markdown documentation compilation.

#### Team Photo
(./team_photo.jpg)
