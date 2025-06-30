# mechanical-horse-brace
🦿 Titanium Equine Leg Brace System (TELBS v2): Full Mechanical-Motion Bio-Support Leg

    Designed to stabilize, support healing, and mechanically assist movement during rehabilitation of an injured equine limb—specifically the forelimb (cannon bone to hoof).

🧩 1. Full Structural Breakdown with Measurements
📏 A. Upper Brace Shell (Above Cannon Bone)

    Position: From upper metacarpus to knee (carpal joint)

    Length: ~200 mm

    Diameter: ~55 mm outer; ~40 mm inner (adjustable for horse size)

    Height from ground: ~550 mm

    Material: Titanium Alloy (Ti-6Al-4V)

    Function:

        Distributes axial load above fracture

        Connects to shoulder sling (if used)

        Houses motion-damper pistons (see Section 5)

📏 B. Main Shaft (Cannon Bone Region Brace)

    Position: Entire length of 3rd metacarpal (cannon bone)

    Length: 280–300 mm

    Wall Thickness: 6 mm titanium, lined with 10 mm memory-gel neoprene

    Diameter: 40 mm internal; ~50–60 mm external

    Function:

        Main structural load bearer

        Attached to actuator rail that mimics bone motion

        Prevents lateral movement during healing

📏 C. Joint Module – Simulated Fetlock (Mechanical Hinge)

    Position: Midpoint where cannon bone meets pastern

    Width: ~60 mm

    Arc Range: ~60° total motion (with limiter for safety)

    Material: Carbon-Fiber Reinforced PEEK composite

    Function:

        Simulates fetlock flexion (heel drop during walking)

        Contains a torsion spring-damper or servo-controlled actuator

        Allows realistic, shock-absorbing gait simulation

📏 D. Lower Shaft (Pastern + Proximal Hoof Support)

    Position: First & second phalanx support, down to coronet band

    Length: ~130 mm

    Diameter: ~30–35 mm

    Material: Titanium + flexible hinge shell at bottom

    Function:

        Transfers motion and force to hoof

        Enables toe-off propulsion during assisted motion

        Holds motion-control rod (see Motion Device below)

📏 E. Smart Shoe Plate / Hoof Connector

    Length/Width: ~140 x 130 mm

    Material: Hardened carbon-steel with graphene rubber pad

    Attached Sensors:

        Force-sensing resistors (FSRs)

        Optional IMU (gyroscope + accelerometer)

    Function:

        Simulates hoof-ground contact

        Syncs gait with actuator response

        Absorbs and redistributes impact during walk

⚙️ 2. Embedded Mechanical Motion System
🛠️ A. Linear Piston Actuator (Mounted in Main Shaft)

    Type: Pneumatic or electromechanical

    Stroke: ~60 mm

    Rated Force: Up to 1,200 N

    Placement: Anchored above and below the cannon bone brace

    Function:

        Contracts to simulate stride

        Retracts during swing phase, extends on stance

        Controlled via hoof IMU + internal processor

🔄 B. Fetlock Joint Assist Spring or Servo

    Spring Type: Torsion bar or hydraulic piston

    Servo Type: Micro-servo (~4–6 Nm torque)

    Function:

        Allows partial flexion during landing

        Helps prevent over-extension of joint during step

        Rebounds slightly to simulate natural lift

🧠 C. Central Motion Processor

    Power: Lithium polymer battery (7.4V, 2000 mAh)

    Logic: Microcontroller (e.g. Arduino Nano, STM32)

    Inputs: IMU, pressure sensors

    Outputs: Actuator, hinge motor

    Function:

        Adjusts movement timing and strength

        Provides “assisted gait” during recovery

        Can be set to passive, partial assist, or full stride modes

💡 3. Healing Support & Load Distribution
Feature	Description
Partial Load Bearing	Reduces pressure on injured leg by 60–80% via distributed shaft structure
No Bone Injection	Relies on mechanical alignment + natural bone healing
Range Limiters	Prevent over-extension via servo-controlled stops
Removable Design	Brace can be detached for inspection or massage treatments
Limb Suspension Add-on	Optional sling connector to reduce total load from shoulder (stall rest)
🧪 Materials List Summary
Component	Material
Brace Shaft/Frame	Titanium Alloy (Ti-6Al-4V)
Hinges & Joints	CF-PEEK Composite
Cushioning	Neoprene + Gel Silicone
Hoof Plate	Carbon Steel + Graphene Pad
Sensors	MEMS IMU, Pressure FSRs
Power Unit	Lithium-ion rechargeable
💰 Estimated Cost Breakdown
Component	Est. Price (USD)
Titanium Frame/Shell	$1,500–2,000
Joint Actuators	$600–800
Motion Processor	$300–500
Sensor Kit	$400
Hoof Plate System	$250–400
Assembly + Fit	$500–1,000
Total	$3,500–$5,500
✅ Final Summary: Key Benefits

    Simulates gait through motorized flexion and spring feedback

    Reduces healing time by offloading pressure while enabling mobility

    Prevents muscle atrophy by encouraging natural joint use

    Non-invasive and modular—no surgical pinning required

    Customizable for racehorses, workhorses, or show horses
