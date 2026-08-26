# Full Self-Driving (Supervised)

Tesla uses billions of miles of anonymous real-world driving data to train Full Self-Driving (Supervised).

Full Self-Driving (Supervised) is currently available in [select markets](https://www.tesla.com/fsd/safety#available-countries) across North America, Europe and Asia Pacific with expansion to additional regions expected with future updates.

[FSD (Supervised)](https://www.tesla.com/fsd) enables your vehicle to drive you almost anywhere with your active supervision, requiring minimal intervention. When engaged and under your active supervision, your likelihood of being in a collision goes down.

- 7x Fewer major collisions

- 7x Fewer minor collisions

- 5x Fewer off-highway collisions

Eight external cameras provide a 360-degree view of the environment around the vehicle. The FSD (Supervised) system then processes over one million pixels of visual data every millisecond so that it can respond in real time to complex and highly variable driving environments.

- **5-Star Safety Ratings**

- **Passive Safety**
  
  - Large crumple zones
  
  - Advanced airbags and seatbelts
  
  - Reduced rollover risk

- **Active Safety**
  
  - Automatic emergency braking
  
  - Driver drowsiness warning
  
  - Over-the-air software updates

- **Fire Safety**
  
  - Battery runaway protection
  
  - Integrated fault responses
  
  - [Proven fire safety record](https://www.tesla.com/VehicleFireSafetyReport)

FSD (Supervised) improves U.S. road safety by over 80%, reducing the likelihood of collisions caused by human error.

- 32,000+ Lives potentially saved per year
  
  [NHTSA](https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/813738) reported 40,900+ fatalities on the road in the U.S. in 2023

- 1,900,000+ Injuries could potentially be avoided per year
  
  [NHTSA](https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/813738) reported 2,400,000+ injuries on the road in the U.S. in 2023

- 30% Of fatalities from drunk driving (2023) [NHTSA](https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/813713)

- 44% Of vehicle-occupant fatalities from not wearing a seatbelt (2023) [NHTSA](https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/813730)

- 29% Of fatalities from speeding (2023) [NHTSA](https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/813721)

- 29% Of collisions from distracted driving (2023) [NHTSA](https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/813403.pdf)

---

**Collision Definition**

Tesla records collision events in accordance with 49 C.F.R. § 563.5, which defines a collision event as a crash or physical occurrence that causes any non-reversible deployable restraint to be deployed or that meets or exceeds the trigger threshold of a change in velocity (Delta-V) of 8 km/h occurring within a 150-millisecond period. Delta-V measures the change in a vehicle's velocity during a collision and is widely used in crash analysis to quantify impact severity. A higher Delta-V indicates greater forces acting on the vehicle and its occupants, making it a reliable indicator for discriminating between impact severities across a broad spectrum of collisions.

Consistent with 49 C.F.R. § 563.5, Tesla separates collisions into two categories:

1. Deployment collisions tend to have higher severity impacts where the vehicle's airbags or other non-reversible pyrotechnic restraints are deployed. Tesla refers to these collisions as “major collisions” in the Vehicle Safety Report.
2. Non-deployment collisions tend to have lower severity impacts (Delta-V ≥ 8 km/h within 150 milliseconds) where neither airbags nor any other non-reversible pyrotechnic restraints are deployed. Tesla refers to these collisions as “minor collisions” in the Vehicle Safety Report.

**Collision Classification**

If FSD (Supervised) was active at any point within five seconds leading up to a collision event, Tesla considers the collision to have occurred with FSD (Supervised) engaged for purposes of calculating collision rates for the Vehicle Safety Report. This approach accounts for the time required for drivers to recognize potential hazards and take manual control of the vehicle. This calculation ensures that our reported collision rates for FSD (Supervised) capture not only collisions that occur while the system is actively controlling the vehicle, but also scenarios where a driver may disengage the system or where the system aborts on its own shortly before impact.

**No Assessment of Fault in the Reported Data**

Tesla does not attribute fault in our collision reporting due to the subjective and complex nature of fault determination, which typically requires detailed investigation of circumstances, driver intent and applicable traffic laws. By reporting all collisions, regardless of who or what factors contributed to the cause of the collision—driver(s), vehicle(s), environment, system misuse, etc.—Tesla provides a consistent and objective measure that allows for meaningful safety comparisons across different driving modes and conditions.

**Comparison to Manually Driven Tesla Vehicles With and Without Active Safety Features**

Tesla compares FSD (Supervised) collision rates, observed by our telemetry, to both manually driven Tesla vehicles with and without active safety features. All Tesla vehicles manufactured after 2014 are equipped with active safety features, including Automatic Emergency Braking, Forward Collision Warning, Lane Departure Warning and other collision-avoidance systems. Tesla’s data reflects substantially higher miles-per-collision rates for Tesla vehicles equipped with active safety features compared to Tesla vehicles without these features.

Tesla vehicles without active safety features (i.e., Tesla vehicles manufactured prior to 2014) serve as the best proxy for the safety of an average U.S. vehicle, given that the average vehicle age in the U.S. is approximately 12 years old, predating widespread adoption of active safety and advanced driver-assistance systems. While these vehicles are not sold anymore, they collectively drive hundreds of millions of miles every year.

**Vehicle Telemetry Presented**

The Tesla fleet is comprised of millions of vehicles worldwide, generating real-world driving data at scale. The Vehicle Safety Report illustrates a combination of anonymous vehicle telemetry, including miles driven, road classifications and control type, in addition to safety-critical event telemetry (VIN-associated data received when the vehicle experiences a major or minor collision, as defined above). To illustrate telemetry volume, in Q3 of 2025 alone, Tesla received 2.5 billion telemetry packages from our vehicle fleet around the world (excluding China).

The vehicle telemetry packages that are analyzed and aggregated in the Vehicle Safety Report occur in two distinct ways:

1. On shift-to-park: The vehicle transmits a data packet containing anonymized mileage information from the culminating trip (or drive cycle) to Tesla servers. This data informs Tesla of the number of miles traveled in different control types and road classifications for each vehicle type.
2. On detection of a major or minor collision: A VIN-associated data packet is transmitted to Tesla servers. If the data upload fails, trip and collision information remains stored on the vehicle itself and is available to reattempt upload if connectivity is restored.

Certain variables, including but not limited to cellular connectivity or damage to vehicle communication systems, may affect Tesla’s ability to capture certain events. Importantly, these variables apply uniformly across all Tesla control types analyzed in the Vehicle Safety Report, preserving the validity of comparative safety metrics between FSD (Supervised) and manual driving.

**Highway and Non-Highway Definition**

Tesla categorizes roadways into highway and non-highway based on road characteristics including map data routing classes, lane count and controlled access infrastructure. While our classification accuracy is high, there may be minor variations in mileage and collision data based on localization, map dependencies and differences in definitions when compared to U.S. averages.

**Calculating a Baseline U.S. Average**

The safety benefits of FSD (Supervised) are clear when compared to manually driven Tesla vehicles with and without active safety features. This is the most direct and statistically valid comparison setup since it is being made within the same fleet of vehicles using the same telemetry pipelines.

Additionally, Tesla vehicles share the road with many road users in non-Tesla vehicles. To that end, it is prudent to assess the safety of FSD (Supervised) against the general safety of roadways in the U.S. A quantifiable means by which to do this is to estimate the U.S. collision rate using data published by the U.S. government, which is the best available source. To establish a baseline U.S. average, Tesla used U.S. government data, as explained below, to estimate for total miles traveled (numerator) and total vehicles involved in a collision (denominator).

The U.S. government publishes several data sources for consideration. For total miles traveled (numerator), a commonly used source for research is the Federal Highway Administration’s (FHWA) vehicle miles traveled (VMT) annual reports (with the most recent publication being for calendar year [2024](https://www.fhwa.dot.gov/policyinformation/statistics/2024/vm202.cfm)). For total vehicles involved in a collision (denominator), Tesla looked to three sampling and reporting systems: the National Highway Traffic Safety Administration’s (NHTSA) Crash Report Sampling System (CRSS), which captures police-reported incident rates nationwide; second, NHTSA’s Crash Investigation Sampling System (CISS), which samples police-reported collisions where at least one passenger vehicle was towed from the crash scene; and third, NHTSA’s Fatality Analysis Reporting System (FARS), which measures fatality events nationwide. Among these sampling and reporting systems, the CISS primarily involves collision severities that most closely align with Tesla’s approach to tracking major collisions, because the CISS captures collisions where at least one passenger vehicle was towed and is not limited by injury outcomes. In contrast, CRSS primarily captures incidents where neither airbags nor other restraints may have deployed (e.g., approximately [71.7%](https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/813762) of crashes in the CRSS for 2023 are property damage only, whereas deployment events are more closely associated with higher severity impacts with greater potential for injury). In further contrast, the FARS is specific to fatal collisions and primarily captures a subset of the highest severity deployment incidents and certain non-deployment or difficult-to-detect incidents involving certain object types.

Based on all these considerations, to calculate the major collision “U.S. average” estimate, Tesla divided the FHWA vehicle miles traveled (from all vehicles reported) by the estimated total count of vehicles involved in CISS-reported incidents (see the total value in Table 3 of the [CISS reports](https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/813769)).

The CISS and FHWA databases do not contain highway and non-highway breakdowns that are directly comparable to Tesla’s data. Therefore, to estimate a baseline for the “U.S. average” collision rate breakdown by highway and non-highway, Tesla computed the relative fraction of the overall collision rate seen in the manually driven Tesla fleet for both highway and non-highway driving. Tesla then applied those fractions to the major collision “U.S. average” rate to estimate the “U.S. average” collision rate for highway and non-highway driving. Tesla applied the same method to estimate the “U.S. average” rate for “Minor Collisions” by using the ratio of minor collisions to major collisions in the Tesla manually driven fleet. The Tesla manually driven fleet is a reasonably representative approximation for these fractions, due to its size (over three million U.S. vehicles), geographic distribution (presence in every U.S. state), owner makeup (Model Y was the second bestselling non-pickup in the U.S. in 2023-2024) and activity (over 30 billion miles annually in the U.S.).

Tesla appreciates that any adjustments to data can potentially introduce inadvertent noise and bias. To preserve the accuracy and integrity of the methodology used to calculate the U.S. average and compare it to Tesla collision rates, Tesla purposely limited any processing or filtering of data to be strictly minimal and only as necessary, as outlined above. Even still, the methodology involves necessary and unavoidable assumptions due to differences in data collection methods between Tesla’s data and publicly available data published by the U.S. government. These assumptions may contain limitations with respect to reporting criteria, unreported incident estimations (e.g., NHTSA estimates that 60% of property damage-only crashes and 32% of injury crashes are not reported to police [[Blincoe et al. 2023](https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/813403)]), federal database sample size and fleet distribution. Some of these limitations may skew the U.S. average calculation higher or lower than presented in the Vehicle Safety Report. Notwithstanding these limitations, the magnitude of improved real-world safety using FSD (Supervised) is clear and undeniable. This is plainly evident in the most direct comparison between Tesla vehicles using FSD (Supervised) and those being driven manually. The U.S. average estimate (even with its limitations) simply reinforces that conclusion.

---

**Why does Tesla collect collision telemetry?**

Tesla collects collision telemetry to understand the nature of real-world collisions and develop solutions to prevent or mitigate them.

**Why doesn’t Tesla share other data (e.g., injuries) in the Vehicle Safety Report?**

Tesla's collision reporting methodology relies on automated telemetry data collected directly from vehicle systems. This approach enables objective collision detection across millions of vehicles. Other data, such as occupant injury information, is inconsistently provided through voluntary reporting by drivers or otherwise inaccessible to Tesla due to health-related privacy laws.

Instead, Tesla focuses on objective and programmatic metrics such as collision frequency and airbag deployment rates. Airbag deployments serve as a reliable proxy for collision severity. For example, airbag deployment thresholds are specifically engineered to activate airbags at impact severities where occupant injury risk increases significantly. Airbag non-deployment collisions typically represent lower severity collisions that may not require an airbag deployment. Together, these make for meaningful and objective safety indicators, which can be consistently measured across the entire fleet of Tesla vehicles. In addition to the regular quarterly updates, Tesla is committed to enhancing the Vehicle Safety Report with additional insights, statistics and reporting methodology.

[Find information on Tesla vehicles’ crash safety](https://www.tesla.com/safety).

**Why does Tesla report the most collisions under NHTSA’s Standing General Order on Crash Reporting (SGO), as compared to other car companies?**

NHTSA’s Standing General Order on Crash Reporting (SGO) requires manufacturers to report known collisions involving a vehicle traveling with an Automated Driving System (ADS) or Advanced Driver Assistance System (ADAS) engaged within the last 30 seconds before a collision occurs, among other reporting criteria. However, the SGO does not require manufacturers to develop a telemetry system to receive notification of collisions involving an ADAS or ADS system. Tesla uses the collision telemetry system described in this Vehicle Safety Report to supplement federal reporting obligations, including the SGO.

Tesla designed its vehicles to maximize connectivity and capability. We use remote telemetry to learn from the vehicle fleet to inform a variety of engineering decisions, including being notified about safety-critical events (such as major or minor collisions). In contrast, other vehicle manufacturers, whose vehicles are less connected, largely do not receive vehicle data when a collision occurs that involves one of their vehicles unless or until a customer tells them or sues them.

The consequence of the SGO’s reporting scheme suggests higher absolute collisions among Tesla vehicles than for every vehicle manufacturer combined; however, the reality is that Tesla reports more collisions simply because we have a large, active and fully connected customer vehicle fleet. This unfortunate consequence of the SGO is compounded by a lack of data normalization. While the SGO requires manufacturers to report absolute collision counts, it does not require manufacturers to report the number of their vehicles operating on U.S. roads or the distance traveled in those vehicles. If one considers absolute collision counts alone, collisions will appear to increase with increased adoption or usage, while in reality, the rate of incidents may be decreasing.

---

If Tesla vehicles are available for sale in your country, but FSD (Supervised) is not yet available, it may be because your country requires explicit regulatory approval from local authorities.

Tesla global fleet of 8.6 million vehicles is actively generating anonymous data from real-world driving scenarios, experiencing more in one minute than a person can experience in one lifetime.

We turn these learnings into safety improvements and share them with all Tesla vehicles through free over-the-air software updates.

**As You Leave**

When you begin your drive, your seat position and mirror preferences automatically adjust to your Driver Profile. Shift into Drive or Reverse and your Tesla will activate your external cameras to show you what’s around your vehicle and how close it is as you move out of your parking spot and onto the road. If an object is detected, you’ll hear a chime.

**Along the Way**

Once you’re on the road, your Tesla will monitor your driving and use chimes and vibrations to help you stay in your lane, keep to the speed limit and know if there is a pedestrian, object or other vehicle in your blind spots. It can even detect and alert you when it notices you getting drowsy in the driver’s seat.

**When Parking**

Repark your vehicle using cameras and Park Assist. Blind spot monitoring also helps when you're opening your door—alerting you and pausing before opening if an object, person or cyclist is approaching.

When you leave, Child Left Alone Detection will set off an alarm if anyone is still inside. Phone Left Behind will chime if you close your door with a phone key left inside. Sentry Mode will watch your vehicle while you’re gone.

---

While you’re driving, active safety features like Forward Collision Warning and Emergency Braking can alert you or take action before things go wrong, helping to prevent accidents or reduce their severity.

Forward Collision Warning uses your vehicle’s front cameras to see if you’re approaching an object, pedestrian or other vehicle too quickly. If a collision is considered likely unless you take immediate corrective action, you’ll hear a warning sound and the vehicle or object in front of you will appear in red on your touchscreen.

If you aren’t taking action and a collision appears to be imminent, your Tesla will activate Automatic Emergency Braking to reduce torque and apply the brakes for you to slow your speed and reduce the severity of impact.

If you're driving over 31 mph and have hit the brakes suddenly, the Dynamic Brake Lights feature will flash your brake lights quickly to warn other drivers that your vehicle is rapidly slowing down, so they have more time to react, too.

---

Some crashes are unavoidable. Impact-absorbing zones around the vehicle, a stiff passenger compartment that minimizes intrusion and advanced seat belts and airbags that deploy within milliseconds all help protect occupants when a collision occurs.

**Prepared for Impact**

The chassis and frame of the vehicle are designed to absorb the energy of a crash before it gets to the cabin. This helps protect occupants and the battery from direct impact energy, reducing the likelihood of injury.

This design also helps reduce impact severity for the other vehicle, keeping its occupants safer.

**Reactive Airbags**

Advanced airbags are tuned to deploy according to crash type and different-sized occupants. This includes active venting that changes the amount of pressure within the inflated cushion by releasing gas according to the expected crash severity.

Additional far-side airbags between first-row occupants help prevent occupant-to-occupant contact during side impacts.

**Safer Seat Belts**

Before a crash occurs, front cameras observe the scenario and prepare the seat belt system to react faster and with adequate force and timing when impact occurs, reducing the amount of slack in each seat belt

The seat belts themselves can also adjust according to detected seat position, helping to control the force on the occupant.

---

**Emergency Response**

When a serious collision is detected, your hazard lights will turn on to increase your visibility and doors will automatically unlock for emergency access. At the same time, your Tesla will automatically contact emergency services to get help to you as quickly as possible.

**Battery Protection**

Tesla vehicle structures are designed to cushion and protect the battery in the event of an accident. Onboard systems will automatically disconnect the high-voltage battery upon impact. If a battery fire does occur, the battery pack is designed to spread heat away from the cabin to protect occupants.

**Real-World Data**

Dashcam clips include details like date, time, driving speed and Self-Driving status. Impact data from crashes is sent to Tesla and used by our safety engineering team to improve and develop new and existing safety features. These learnings and developments are then shared with every Tesla vehicle in our global fleet through over-the-air software updates—so your Tesla gets better and safer over time.

Data is anonymized and aggregated and requires sharing to be enabled.

---

**Cabin Camera**

The cabin camera is located above the rear-view mirror in the following vehicles:

- Model S (produced in 2021 or later)
- Model 3
- Model X (produced in 2021 or later)
- Model Y
- Cybertruck

For these eligible vehicles, the cabin camera can determine driver inattentiveness and enhance active safety features. To protect your privacy, images and video from the cabin camera do not leave the vehicle itself and are not transmitted to anyone, including us, unless you enable data sharing.

If you choose to enable data sharing, in the occurrence of a serious safety risk or a safety event like a collision, the vehicle can share images and short video clips with us to help develop future safety features and software enhancements, such as collision avoidance.

The cabin camera images you share with us are not linked to your VIN and will be used to continuously improve the intelligence of features that rely on cabin camera. You may change your data sharing settings at any time.

**Security Alarm**

Your alarm will sound and external lights will flash if a locked trunk or door is opened without a valid entry key.

Your vehicle will enable the alarm one minute after you exit, the doors will lock and a recognized key will no longer be detected in or near the vehicle.

To stop your vehicle alarm, unlock the doors using your key fob, key card or the [Tesla app](https://www.tesla.com/support/tesla-app).

**PIN to Drive**

PIN to Drive allows you to set a secure four-digit verification that must be entered before your vehicle is driven.

If you forget your PIN or want to disable PIN to Drive, go back to the setting on your touchscreen. Tap the link to enter your Tesla login credentials and follow the on-screen prompts.

**Sentry Mode**

Sentry Mode is a feature that allows you to monitor activities around your Tesla vehicle when it’s parked and locked. When suspicious motion is detected, your vehicle will react depending on the severity of the threat.

If a threat is detected, the cameras on your vehicle will begin recording, and the alarm will activate. If the alarm is activated, you will receive an alert from the Tesla app notifying you that an incident has occurred.

You can also enable Sentry Mode via [Voice Command](https://www.tesla.com/support/voice-commands) or the Tesla app. Unless at a Supercharger, Sentry Mode will remain active until the vehicle is at or below 20% battery. The Tesla app will notify you if Sentry Mode is disabled due to low battery.

**Note:** It is your sole responsibility to consult and comply with all local regulations and property restrictions regarding the use of cameras.

With Live Camera, remotely view your vehicle’s surroundings when it’s parked to confirm the safety of the environment before you return to your vehicle. You can also honk your horn, flash your lights and talk through the vehicle’s speaker if you have one equipped. Live Camera is end-to-end encrypted and cannot be accessed by us. This feature is available on iOS and Android devices with the Tesla app version 4.2.1 or later and requires [Premium Connectivity](https://www.tesla.com/support/connectivity). Live Camera is not available on Model S and Model X vehicles produced 2012-2020.

Sentry Mode is designed to add another layer of protection to your vehicle, but it will not prevent all possible threats.

**Note:** Pet Mode and Sentry Mode cannot be active at the same time.

**Note:** Sentry Mode will not record if your dashcam is not properly installed and equipped with a USB drive. [To install your dashcam, follow these steps](https://www.tesla.com/support/vehicle-safety-security-features#dashcam).

**Require Manual Entry**

An authenticated phone key will use its Bluetooth signal to unlock your vehicle doors as you approach the vehicle.

**Intrusion Sensors**

Our security system and [Sentry Mode](https://www.tesla.com/support/vehicle-safety-security-features#sentry) come standard on every new Tesla vehicle; these systems can detect and alert you of suspicious activity around your vehicle. For added layers of protection, all new Tesla vehicles come with intrusion sensing hardware; for some vehicle trims, these systems will be activated with future over-the-air updates.

---

Our global data indicates that, between 2012 and 2023, approximately one Tesla vehicle fire event occurred for every 135 million vehicle miles traveled. By comparison, data from the NFPA and U.S. Department of Transportation indicate that one vehicle fire occurs in the United States for every 17 million miles traveled. Compared to average vehicles on the road, Tesla vehicles are comparatively even less likely to be involved in a fire event than these numbers suggest, because Tesla's data includes fire events that are caused by structure fires, wildfires, arson, and other causes unrelated to the vehicle, whereas the NFPA data excludes any fires where a structure is involved.

---

Full Self-Driving (Supervised) intelligently and accurately completes driving maneuvers for you, including route navigation, steering, lane changes, parking and more under your active supervision. Use it for quick errands, daily commutes and road trips. Currently enabled features require active driver supervision and do not make the vehicle autonomous.

Activate in the Tesla app and your Tesla vehicle will navigate through parking lots and tight spaces to get to you.

On-board cameras with 360-degree visibility will check your blind spots and move your Tesla vehicle into a neighboring lane while maintaining your speed and avoiding bikes, motorcycles and other cars.

Your Tesla vehicle will automatically detect and maneuver into perpendicular and parallel parking spots for you.

Crashes are complex. Full Self-Driving (Supervised) is trained on what amounts to over 100 years of anonymous real-world driving scenarios from our fleet of over six million vehicles. Our fleet collectively experiences a lifetime of driving scenarios in 10 minutes.

Cameras don’t blink, feel tired or get distracted. Full Self-Driving (Supervised) helps you drive better by taking care of the most common and error-prone driving tasks. Tesla vehicles are equipped with exterior cameras that enable 360-degree visibility, plus safety features powered by the same technology as our FSD software to help reduce the severity of accidents or prevent them altogether. Over-the-air software updates ensure each Tesla vehicle has access to the latest safety improvements.

---

How long does FSD (Supervised) suspension last?

If improper usage of FSD (Supervised) is detected, driving habits are deemed unsafe or any terms of the FSD (Supervised) agreement have been violated, use of the features will be suspended for a week when you or another driver of your vehicle receives three or five strikeouts, depending on vehicle configuration.

A strikeout is when the Self-Driving system disengages for the remainder of a trip after the driver receives several audio and visual warnings for inattentiveness. A strikeout is forgiven after half a week, as long as you do not receive another strikeout for your vehicle in that time.

If your access to FSD (Supervised) is suspended, the FSD (Supervised) toggle will display a message that your suspension is active.

Once your suspension is over and the message has been removed, you will regain access to FSD (Supervised).
