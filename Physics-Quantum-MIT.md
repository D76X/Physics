# MIT OpenCourseWare

[Quantum Physics I \- MIT OpenCourseWare \- Prof. Barton Zwiebach](https://ocw.mit.edu/courses/8-04-quantum-physics-i-spring-2016/)   

[MIT 8.04 Quantum Physics I, Spring 2016 \- YouTube Playlist](https://www.youtube.com/playlist?list=PLUl4u3cNGP60cspQn3N9dYRPiyVWDd80G)

### [Galilean transformation of ordinary waves](https://www.youtube.com/watch?v=YdtHAIh-kas&t=609s)

[Phase invariant under Galilean transformation? \- **StackExchange Physics**](https://physics.stackexchange.com/questions/702145/phase-invariant-under-galilean-transformation)   

[Why is the phase of a matter wave not Galilean invariant? And what does this say about the Schrödinger equation? \[duplicate\] \- **StackExchange Physics**](https://physics.stackexchange.com/questions/635054/why-is-the-phase-of-a-matter-wave-not-galilean-invariant-and-what-does-this-say) 

[Physics-Quantum-MIT8\_04S16\_LecNotes4.pdf](https://drive.google.com/file/d/1ZWnXx6jaoIqalNHyJMN06r4opBv4V2LJ/view?usp=drive_link) 

**For ordinary waves** **that propagate in the rest frame of a medium,** like sound waves or water waves, Galilean observers will find frequency changes but no change in wavelength. 

**This is intuitively clear**: to find the wavelength, one needs only take a picture of the wave at some given time, and both observers looking at the picture will agree on the value of the wavelength. On the other hand, to measure frequency, each observer must wait some time to see a full period of the wave go through them. This will take a different time for different observers

#### Is the phase of a wave a Galilean invariant?

**No, the phase of a wave is not generally Galilean invariant.** 

While the phase of a **classical wave**, like a water wave, is often considered a Galilean invariant, **the phase of matter waves (like in quantum mechanics)** **and electromagnetic waves is not**. 

**The Galilean transformation leads to a non-invariant phase for matter waves** due to their transformation properties under boosts. In contrast, **classical wave phase invariance is limited and does not hold for electromagnetic waves**, which required the development of the Lorentz transformations.

**Classical Waves**

* **Water Waves**: The phase of a water wave can be considered Galilean invariant in certain contexts, as all observers in different inertial frames would agree on the points of zero-crossing or the overall structure of the wave.   
    
* **Electromagnetic Waves**: The phase of electromagnetic waves, such as light, **is not Galilean invariant**. Maxwell's equations, which describe these waves, are not preserved under Galilean transformations, indicating that the wave's phase is not the same for all observers in relative motion.

**Matter Waves (Quantum Mechanics)** 

* **Not Galilean Invariant**: The phase of matter waves is not Galilean invariant. When a Galilean transformation is applied to a matter wave, the wave's phase changes, which is crucial for the structure and behaviour of quantum systems.  
    
* **Schrödinger Equation**: The phase transformation of a matter wave under a Galilean boost is given by an additional factor, e^(im₀/ħ)(ux \- ½u²t), which is not a simple phase transformation and deviates from Galilean invariance.

#### Why is the phase of a classical wave, such as a water wave, a Galilean invariant?

Ref: [https://ocw.mit.edu/courses/8-04-quantum-physics-i-spring-2016/resources/mit8\_04s16\_lecnotes4/](https://ocw.mit.edu/courses/8-04-quantum-physics-i-spring-2016/resources/mit8_04s16_lecnotes4/) 

The phase of a classical wave is a Galilean invariant because the physical quantity it represents, such as the height of a water wave at a given point, is observed to have the same value by all observers in different inertial frames. 

**When two observers are in uniform motion relative to each other**, they can both observe and agree on the location of a wave's peaks or troughs, meaning the phase value remains unchanged under a Galilean transformation, which is the defining characteristic of an invariant quantity in classical mechanics.

**What is Galilean invariance?**

* **Principle of Relativity**: It is a cornerstone of classical mechanics, stating that the laws of physics, including the equations of motion for closed systems, are the same in all inertial frames of reference.   
    
* **Inertial Frames**: These are frames of reference where an object at rest stays at rest, and an object in motion continues in motion with constant velocity, unless acted upon by a net force.   
    
* **Galilean Transformation**: This is a transformation between inertial frames that describes how coordinates and time change when one frame is moving at a constant velocity relative to another.

**How does it apply to the phase of a wave?** 

* **Physical Reality**: A wave's phase describes its state at a particular point in time and space. For example, the height of a water wave, which is a physical manifestation of its wave, has a real, measurable value.  
    
* **Observer Independence**: The Galilean principle requires that physical quantities should not change their fundamental nature or value when observed from different inertial frames.  
    
* **Agreement on Phase**: Therefore, two observers moving at different, constant velocities relative to each other will agree on the specific phase value at any point in the wave. For instance, if one observer sees a wave crest, another observer in a different inertial frame will also see that same crest.

---

### [The Frequency of Matter Waves](https://www.youtube.com/watch?v=3_qvO8bKGus&t=323s)

---

#### What is the meaning of the phase of a wave?

**DeepSeek**

I have the following equation that is used to define the concept of phase of a classical wave.

ϕ(x,t) \= k(ω,x,t)⋅x−ω(k,x,t)⋅t+ϕo

The equation comes from this source: [https://physics.stackexchange.com/questions/384276/understanding-group-velocity](https://physics.stackexchange.com/questions/384276/understanding-group-velocit)  

And the author describes the phase of a wave as follows: **It is the position on a wave cycle between a crest and a trough**.

**Please help me better understand the meaning of this definition.**

**Answer Summary** 

The equation provides the mathematical machinery to describe that intuition in a wide range of situations.

1. **Position on a wave cycle: the intuitive meaning**

Phase (φ) is a number together with the unit radians or degrees that measures which part of the repeating cycle of a wave you are looking at, given a specific place, the coordinate x, and a specific value for the time t.

Imagine you are an observer in a reference frame. When the values of x and t are chosen and plugged into the phase equation, the result tells how distant the observed point on the wave is from the beginning of the wave cycle it belongs to.

**How does this equation create a wave?**

1. **Freeze Time (take a snapshot)**

If you **take a picture of the wave at a single moment** in time (t is fixed), **the phase changes with position x**. 

**Moving a distance Δx changes the phase by kΔx**.   
(This spatial repetition is the wavelength.)

2. **Freeze Position (watch one point)**  
   

If you stand at one location and watch the wave go by (x is fixed), the phase changes with time t. Waiting for a time Δt changes the phase by ω\*Δt. This temporal repetition is the period of the wave.

---

**The most general form of the phase equation for an ordinary wave**

ϕ(x,t) \= k(ω,x,t)⋅x − ω(k,x,t)⋅t \+ ϕ₀

The key in this equation is that k and ω are written as functions: 

- k(ω, x, t)   
- ω(k, x, t) 

This is necessary to **describe a wave propagating in a complex medium where the properties of the wave can change**.

* Waves propagating in a simple, uniform medium like a perfect string or vacuum, **k and ω are simple constants**. In this case, **the relationship between them** is ω \= v\*k, where v is the wave speed, and this relationship is fixed.   
    
* Waves propagating in a complex medium like water of varying depth, the atmosphere, an optical fibre, or a plasma, the relationship between k and ω, **called the dispersion relation,** can be more complicated. Furthermore, the wave's properties, its **speed and wavelength**, can change depending on any of the following factors:

- **Frequency (ω):** **This is dispersion**. 

  Different colours of light travel at different speeds in glass, which is why a prism splits white light.


- **Position (x): The medium might not be uniform**. 

  The speed of sound changes with air temperature, which varies with location.


- **Time (t): The medium itself might be changing**, like the density of the air in a vibrating speaker box.

---

#### What is the meaning of group velocity?

[Understanding group velocity \- Physics StackExchange](https://physics.stackexchange.com/questions/384276/understanding-group-velocity)  
[https://en.wikipedia.org/wiki/Group\_velocity\#/media/File:Wave\_opposite-group-phase-velocity.gif](https://en.wikipedia.org/wiki/Group_velocity#/media/File:Wave_opposite-group-phase-velocity.gif) 

Let us define some relevant parameters:

* **Wave Number ≡  k=k(ω,x,t)**


It measures **the number of wave crests per unit length**, which is **akin to a density of waves.** 

It indicates **the number of radians of phase change per meter in space**.   
It is related to the wavelength (λ) by **k \= 2π/λ**.   
A short wavelength, therefore a tightly packed wave, means a large k.

* **Wave Frequency ≡ ω=ω(k,x,t)**


It measures **the number of wave crests crossing position x  per unit time**, which is **akin to a flux of waves**.

It indicates **the radians of phase change per second**.   
It is related to the period (T) and frequency (f) by ω \= 2πf \= 2π/T.   
A high frequency means a large ω.

* **Wave Phase ≡  ϕ(x,t) \= k(ω,x,t)⋅x−ω(k,x,t)⋅t+ϕo**


It is the position on a wave cycle between a crest and a trough.  
Φ₀ is the initial phase or phase constant.   
Φ₀ is the phase at the origin (x=0) at the start of time (t=0).   
Φ₀ just sets a global reference point for the wave.

* Wave Amplitude ≡  A=A(k,ω,x,t)


It is one-half the distance between the crest and trough for a symmetric, linear wave (though in most cases, A is a constant).

[**Group and phase velocity \- Scholarpedia**](http://www.scholarpedia.org/article/Nonlinear_wave#Group_and_phase_velocity)