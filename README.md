# advanced_optimization_pmu_wip
Thoughts on future development, Phase II 
Possible future development 
Notes and thoughts 
After completion of phase I
Big goals
Issues to overcome
Supporting modules 
Separate control without effect to other systems in an adverse way
Controllably 
Manageable strategy
4D modeling
Flow dynamics 
Atomic accounting 
Precision & Flexibility
Current strategy do not allow for anything other than a plane-1 Instead of following a plane-1 target a point on the plane.
Thought is toward the ability to target a point on the plane and not follow a single linear line array 
Rather allowing for a flexable strategy that can control the rate of current as needed for better management of the state of charge,the rate of charge induced and the rate of charge drain.
For a 4D model this may be possible as the "linear" plane can be tracked and monitored.
The target empty and target max models can be designed based on the parameters that can be used to characterize the coefficients and the laws of the coefficients to a 3D model similar to a cube, but more flexible and dynamic
The exact qualities of the empty target and the exact qualities of the the full target will characterize the linear plane of the 4th dimensional plane or the linear plane-1
The linear plane will be able to represent the level of the state of charge as it tracks the current induced or the current drained
being able to know the exact qualities of the target can flexibly manage the current flow with reference sensors used for temperature managment, current flow managment.
Flexible coefficient's controllable for rate of induction and rate of drain so that the model would be more like a fluid dynamics model as current flow is more characteristically like a fluid or the current of a river 
The electrons are the constant flow of of substance and the wires and resistance are the pipes restricting the current or limiting the flow in a <---negative direction, upward with amperage, downward with volts
The size of the pipes voltage and amperage control the rate of flow ---> positive direction toward the negative as a river flows down stream within its banks and its banks are not always the same width or depth. Upwards with current induced, downward with current drained.
When current is not needed the voltage and amperage will be decreased. When current is needed voltage and amperage will be increased. Just as cpu and gpu frequencies can be ramped up or down so to can voltage. With pwm regulators and use of capacitors for reserves and buffering.Using parallel circuitry dividing the loads and looking at the architectural design and limitations. Revisiting the design for possible performance gains and simplify when possible. Looking for the weak link and improving the weak link where possible.Looking for a new angle towards the situation that causes the limiting factor.
This will require the use of %shaders, which is not currently supported to this extent.A new module and a new support for arrays and view creation.As standard arrays will not tolerate such flexibility
V2 TTL DMM required 
Invesense using sensors at our disposal. Coding "KISS" style, simplicity when possible for performance. Coding for limiting intrusive behavior causing unwanted drain with stability and performance an equal goal. 
Thoughtful design. Testing of current platforms for proof of concept. Keeping newer designs in mind. Applying proof of concept to new technology.
