# MvxdEngine

The best order to create a 3D game engine depends on your goals, but here’s a solid roadmap to follow:
*Roadmap that ChatGPT gave me and ill just follow it along very likely*

### **Phase 1: Core Foundation**
1. **Windowing System**  
   - Use libraries like SDL, GLFW, or custom platform-specific code *For 1st chatGPT told me to use a library and ill use it for a bit but im going to build a windowing system on my own by using WinAPI*.
   - Handle window creation, resizing, and closing.

2. **Rendering Engine (Basic Setup)**
   - Initialize OpenGL, Vulkan, or DirectX.
   - Create a basic rendering pipeline with a triangle.

3. **Input Handling**
   - Capture keyboard, mouse, and gamepad inputs.
   - Implement event-driven or polling-based input systems.

4. **Basic Resource Management**
   - Load shaders from files.
   - Implement a basic asset manager.

---

### **Phase 2: 3D Rendering Pipeline**
5. **Camera System**
   - Implement a simple FPS-style or orbital camera.
   - Support projection and view transformations.

6. **Model Loading**
   - Implement a simple OBJ or glTF loader.
   - Support basic materials and textures.

7. **Lighting System**
   - Implement Phong shading (diffuse, specular, ambient).
   - Add support for directional, point, and spotlights.

8. **Entity System (ECS or OOP)**
   - Decide on ECS (Entity-Component-System) or traditional OOP.
   - Implement basic game objects with transform properties.

---

### **Phase 3: Advanced Rendering & Scene Management**
9. **Shadow Mapping**
   - Implement depth-based shadow mapping.
   - Optimize performance using cascaded shadow maps (CSM).

10. **Post-Processing Effects**
   - Add bloom, motion blur, depth of field.
   - Implement HDR rendering.

11. **Scene Management**
   - Create a scene graph to handle hierarchical transformations.
   - Implement frustum culling for performance optimization.

---

### **Phase 4: Physics & Animation**
12. **Collision Detection & Physics**
   - Implement AABB and raycasting.
   - Integrate a physics engine (Bullet, PhysX, or custom).

13. **Skeletal Animation**
   - Implement bone-based animations with interpolation.
   - Support animation blending.

---

### **Phase 5: Game Logic, UI, & Networking**
14. **Scripting System**
   - Integrate Lua or Python for game logic.
   - Expose engine functionality to scripts.

15. **User Interface System**
   - Create a basic UI framework (buttons, text, sliders).
   - Implement font rendering using bitmap or SDF fonts.

16. **Networking**
   - Implement basic multiplayer (TCP/UDP).
   - Sync game state across clients.

---

### **Phase 6: Final Touches**
17. **Optimization**
   - Implement multithreading for rendering & physics.
   - Optimize asset streaming.

18. **Editor / Tools**
   - Build a simple level editor.
   - Create debugging tools like in-game console & profiler.
