# Ex.No.9 – Exploration of Prompting Techniques for Video Generation

**Date:** 28/08/2026
**Reg. No.:** 212223060161

## Aim

To explore different prompting techniques for AI-based text-to-video generation and demonstrate how precise prompts can be used to reproduce the important visual and temporal characteristics of a reference video.

## AI Tools Required

1. **OpenAI Sora** – AI-based text-to-video generation.
2. **Google Veo** – Text-to-video generation and video creation.
3. **Runway** – AI-based video generation and editing.
4. **Stable Video Diffusion** – AI video generation model.
5. **Web Browser** – To access the selected AI video-generation platform.

## Explanation

AI-based video generation uses generative models to create video sequences from natural-language prompts. Unlike image generation, video prompting must describe both **spatial information** and **temporal information**.

Important prompt parameters include:

* Subject and objects
* Environment and background
* Camera angle
* Camera movement
* Lighting
* Color palette
* Texture and visual appearance
* Motion and action
* Duration
* Frame composition
* Video style
* Temporal consistency

The experiment begins with a simple prompt and progressively adds visual and motion-related details to obtain a more controlled video output.

## Procedure

### 1. Analyze the Reference Video

Examine the reference video and identify:

* **Subjects:** People, animals, vehicles, objects, etc.
* **Environment:** Indoor, outdoor, laboratory, city, nature, etc.
* **Colors:** Dominant colors and contrast.
* **Lighting:** Daylight, artificial lighting, shadows, highlights.
* **Composition:** Foreground, background, focal point, perspective.
* **Camera:** Close-up, medium shot, wide shot, aerial view.
* **Camera movement:** Pan, tilt, zoom, tracking, static camera.
* **Motion:** Walking, running, rotating, flowing, moving objects.
* **Style:** Realistic, cinematic, animated, artistic, documentary, etc.
* **Temporal behavior:** Speed and sequence of actions.

---

## 2. Naive Prompt

A naive prompt provides only a general description.

**Prompt:**

> "A futuristic robot moving inside a laboratory."

**Expected Output:**

A short video showing a futuristic robot inside a laboratory.

**Observation:**
The result may not accurately reproduce the desired camera angle, lighting, robot movement, or laboratory environment.

---

## 3. Basic Refined Prompt

Add subject, environment, lighting, and action.

**Prompt:**

> "Generate a realistic video of a humanoid robot walking inside a modern technology laboratory. The laboratory contains electronic equipment and computer displays. Use bright indoor lighting and a clean futuristic environment."

**Observation:**
The generated video becomes more relevant because the prompt specifies the subject, environment, appearance, and lighting.

---

## 4. Advanced Prompt

Add camera movement, composition, motion, and cinematic characteristics.

**Prompt:**

> "Create a realistic cinematic video of a humanoid robot slowly walking through a modern electronics laboratory. The laboratory contains workbenches, circuit boards, measurement instruments, computer monitors, and robotic equipment. Use cool indoor lighting with realistic reflections on metallic surfaces. Begin with a medium-wide camera shot and smoothly track the robot from the front as it walks forward. Maintain stable camera movement, realistic shadows, natural object motion, consistent robot appearance, and high-detail textures. Use a professional technological atmosphere with a clean and futuristic visual style."

**Expected Output:**

A cinematic laboratory sequence containing a humanoid robot with controlled movement, realistic lighting, and smooth camera tracking.

---

## 5. Motion-Focused Prompt

Video generation requires explicit temporal instructions.

**Prompt:**

> "A humanoid robot stands inside a futuristic electronics laboratory. The robot begins walking slowly toward the camera while its arms move naturally. The camera smoothly tracks backward at the same speed, maintaining the robot at the center of the frame. Laboratory displays remain stable in the background. Use realistic human-like motion, consistent lighting, smooth transitions, and no sudden camera movements."

**Observation:**
Adding motion instructions improves control over the temporal behavior of the generated video.

---

## 6. Camera-Control Prompt

**Prompt:**

> "Generate a cinematic 8-second video of a humanoid robot working in a futuristic laboratory. Start with a wide establishing shot, slowly move the camera forward toward the robot, and finish with a medium shot. Keep the robot centered and maintain consistent proportions throughout the sequence. Use realistic laboratory lighting, shallow depth of field, subtle reflections, and smooth camera motion."

**Camera Parameters:**

* Shot: Wide → Medium
* Movement: Slow forward tracking
* Subject: Centered
* Duration: 8 seconds
* Style: Cinematic realism

---

## 7. Iterative Prompting

After generating the first video, identify differences between the reference and generated video.

### Initial Result Issue

* Robot movement is too fast.
* Camera movement is unstable.
* Background contains unnecessary objects.

### Refinement Prompt

> "Regenerate the video with slower and more natural robot movement. Keep the camera stable and smoothly track the robot. Simplify the laboratory background and remove unnecessary objects. Maintain consistent robot proportions and lighting throughout the entire video."

### Further Refinement

> "Maintain the same robot design and laboratory environment. Reduce motion speed further, use smooth cinematic tracking, preserve the original composition, and prevent changes in the robot's appearance between frames."

**Observation:**
Iterative prompting helps reduce unwanted variations and improves similarity to the reference video.

---

# Prompt Comparison

| Prompt Type | Information Provided             | Control Level | Expected Similarity |
| ----------- | -------------------------------- | ------------- | ------------------- |
| Naive       | Subject only                     | Low           | Low                 |
| Basic       | Subject + environment            | Moderate      | Moderate            |
| Refined     | Subject + environment + lighting | High          | High                |
| Advanced    | Visual + motion + camera         | Very High     | Very High           |
| Iterative   | Previous output + corrections    | Very High     | Highest             |

## Video Evaluation Parameters

The generated video can be evaluated using the following parameters:

| Parameter             | Evaluation                                |
| --------------------- | ----------------------------------------- |
| Subject similarity    | How closely the main subject matches      |
| Background similarity | Similarity of environment                 |
| Color similarity      | Matching color palette                    |
| Lighting              | Similarity of illumination and shadows    |
| Composition           | Similarity of framing and perspective     |
| Motion                | Similarity of object movement             |
| Camera movement       | Similarity of pan, tilt, zoom or tracking |
| Temporal consistency  | Stability between consecutive frames      |
| Overall quality       | Visual realism and clarity                |

## Comparison Report

| Feature      | Reference Video       | Generated Video                    |
| ------------ | --------------------- | ---------------------------------- |
| Main Subject | Humanoid robot        | Humanoid robot                     |
| Environment  | Technology laboratory | Futuristic laboratory              |
| Lighting     | Laboratory lighting   | Cinematic indoor lighting          |
| Camera       | Reference-dependent   | Smooth tracking camera             |
| Motion       | Reference-dependent   | Slow robot movement                |
| Visual Style | Realistic             | Cinematic realistic                |
| Similarity   | Target                | Improved through prompt refinement |

## Optimization Technique

An effective video prompt can be structured as:

**Subject + Action + Environment + Appearance + Lighting + Camera + Motion + Duration + Style + Constraints**

### Optimized Prompt

> "Create an 8-second photorealistic cinematic video of a humanoid robot walking slowly through a modern electronics laboratory. Include circuit boards, laboratory instruments, computer displays, and robotic equipment in the background. Use realistic indoor lighting, metallic reflections, natural shadows, and detailed textures. Begin with a wide establishing shot and smoothly track the robot from the front as it moves forward. Keep the robot centered, maintain consistent proportions and appearance throughout the sequence, and use smooth natural motion without sudden camera movements or scene changes."

## Deliverables

1. Original/reference video.
2. Final AI-generated video.
3. Naive, basic, refined, and advanced prompts.
4. Iterative refinement prompts.
5. Comparison report.
6. Observations on visual and temporal consistency.
7. Final optimized prompt.

## Result

Different prompting techniques for AI-based video generation were successfully explored. The video-generation prompts were progressively refined by adding **subject, environment, lighting, camera movement, object motion, duration, visual style, and temporal constraints**. The generated outputs were compared with the reference video to identify differences and improve the prompts.

## Conclusion

The experiment demonstrated that effective prompt engineering can significantly improve the control and quality of AI-generated videos. Basic prompts provide general results, whereas detailed prompts containing **visual, temporal, camera, motion, and stylistic information** produce more controlled outputs. Iterative prompting further improves similarity and consistency between the reference and generated videos. Thus, prompt engineering is an important technique for practical applications such as education, advertising, simulation, filmmaking, and creative content generation.
