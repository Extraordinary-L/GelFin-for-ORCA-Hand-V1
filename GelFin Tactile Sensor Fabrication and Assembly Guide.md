# GelFin Tactile Sensor: Fabrication and Assembly Guide

## Step 1: Material and Component Preparation

Prepare the following materials and components for sensor fabrication and assembly:

- **Sensor Housing:** Fabricated using stereolithography (SLA) 3D printing.
- **Camera:** A fixed-focus camera with a 120° field of view (FOV). Request the supplier to provide accessible positive and negative solder pads on the camera's flexible printed circuit (FPC) cable for powering the LED illumination system.
- **LED Strips:** Two optional illumination configurations:
  - 2 red LEDs + 2 blue LEDs
  - 2 red LEDs + 2 blue LEDs + 2 green LEDs
- **Mirror:** Cut to the specified rectangular dimensions.
- **Acrylic Plate:** Fabricated by laser cutting according to the sensor design.
- **Silicone Mold:** Fabricated using SLA 3D printing or computer numerical control (CNC) machining.

## Step 2: Fabrication of the Silicone Sensing Layer

### 2.1. Silicone Preparation and Mixing

1. Estimate the required mass of silicone elastomer based on the mold dimensions and target sensing-layer geometry.
2. Prepare **Westru 0030** two-part silicone elastomer. Slowly dispense Part A and Part B into a mixing container at a **1:1 mass ratio**.
3. Measure the total mass of the mixing container and silicone mixture.
4. Place the container in a planetary centrifugal mixer and mix thoroughly to obtain a homogeneous silicone mixture.

### 2.2. Degassing and Curing

1. Transfer the mixing container into a vacuum chamber to remove entrapped air bubbles.
2. Carefully pour the degassed silicone mixture into the prepared mold, ensuring complete filling and minimizing air entrapment.
3. Place the filled mold in an oven maintained at **40°C** to accelerate the curing process.
4. After the silicone has sufficiently cured, remove the formed silicone layer from the mold.

### 2.3. PET Marker Pattern Integration

1. Place a polyethylene terephthalate (PET) film onto a suitable release liner.
2. Use a laser cutting system to define the desired marker-dot pattern in the PET film, ensuring that the individual markers remain attached to the release liner.
3. Apply a thin layer of silicone-compatible adhesive to the exposed surfaces of the PET markers.
4. Carefully invert the release liner and align the adhesive-coated markers with the silicone sensing layer.
5. Gently press the markers onto the silicone surface to ensure adequate adhesion.
6. Once the adhesive has set, carefully remove the release liner, leaving the PET marker pattern bonded to the silicone sensing layer.

### 2.4. Opaque Coating Application

1. Apply a uniform layer of opaque ink to the designated surface of the silicone sensing layer.
2. Ensure sufficient optical opacity to suppress interference from ambient light while maintaining the intended internal RGB illumination conditions.
3. Allow the coating to dry or cure completely before proceeding with sensor assembly.

## Step 3: Sensor Assembly

### 3.1. Optical Component Installation

1. Position the mirror, camera, and LED strips at their designated mounting locations inside the bottom housing.
2. Secure these components using **502 cyanoacrylate adhesive**, taking care to maintain the designed optical alignment and avoid adhesive contamination of the optical surfaces.
3. Apply light-blocking tape above the LED strips to minimize unwanted light leakage.

### 3.2. Sensing Layer Integration

1. Insert the laser-cut acrylic plate into the top cover and secure it using 502 cyanoacrylate adhesive.
2. Apply silicone-compatible adhesive to the bonding interface between the silicone sensing layer and the acrylic plate.
3. Carefully align and attach the silicone sensing layer to the acrylic plate, ensuring uniform contact and avoiding trapped air bubbles.
4. Secure the assembled top cover to the bottom housing using screws.

### 3.3. Electrical Connections and Final Assembly

1. Connect the positive and negative terminals of the LED strips to the corresponding preconfigured solder pads on the camera's FPC cable using insulated wires.
2. Verify the polarity and electrical continuity of all connections before applying power.
3. Perform a preliminary power-on test to confirm proper LED operation.
4. Once the electrical connections have been verified, encapsulate the solder joints with hot-melt adhesive to provide electrical insulation and mechanical protection.
5. Inspect the assembled sensor to ensure proper component alignment, secure mechanical connections, and consistent internal illumination.

## Bill of Materials

### 1. Sensor Components

| No. | Component | Specification | Manufacturing Method / Notes |
|:---:|:---:|:---:|:---:|
| 1 | Bottom Housing | Photopolymer Resin | SLA 3D Printing |
| 2 | Top Cover | Photopolymer Resin | SLA 3D Printing |
| 3 | Camera Module | 120° FOV, Fixed-Focus | FPC Cable with Reserved Power Solder Pads |
| 4 | LED Illumination System | Red, Blue, and Optional Green LEDs | Configuration A: 2R + 2B; Configuration B: 2R + 2B + 2G |
| 5 | Mirror | Rectangular | Precision Cutting |
| 6 | Acrylic Plate | PMMA, Thickness: 3mm | Laser Cutting |
| 7 | Silicone Sensing Layer | Westru 0030 Silicone Elastomer | Casting and Thermal Curing |
| 8 | PET Marker Array | Laser-Cut PET Film | Laser Cutting and Adhesive Bonding |
| 9 | Mounting Screws | M1, Length: 5mm | Top Cover Fastening |
| 10 | Electrical Wires | Insulated Conductors | LED Power Connections |

### 2. Fabrication Materials and Consumables

| No. | Material | Specification | Application |
|:---:|:---:|:---:|:---:|
| 1 | Silicone Part A | Westru 0030, Part A&B | Silicone Sensing Layer |
| 2 | PET Film | Thickness: 1mm | Marker Fabrication |
| 3 | Release Liner | Compatible with PET Film | Marker Transfer |
| 4 | Silicone Adhesive | Silicone-Compatible Adhesive | Marker and Sensing Layer Bonding |
| 5 | Cyanoacrylate Adhesive | 502 Instant Adhesive | Mechanical Component Fixation |
| 6 | Opaque Ink | Light-Blocking Coating | Ambient Light Isolation |
| 7 | Light-Blocking Tape | Opaque Adhesive Tape | LED Light Leakage Prevention |
| 8 | Hot-Melt Adhesive | Electrically Insulating | Solder Joint Protection |