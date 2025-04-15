---
title: IQL Design System
---
## 🧾 IQL Design System – Case Study Outline

### 1. **Cover / Intro Slide**

![[IQL Design System.png]]

- **Title**: _“Building the IQL Design System: A Scalable, Token-Driven System for Healthcare SaaS”_
    
- **Subtitle**: Optional one-liner about the impact
    
- **Your role**: Senior UX Designer, System Lead
    
- **Timeline**: e.g. Sept 2024 – Jan 2025

https://www.figma.com/design/0lJzz8wZ01rleoSvuaaVtN/IQL-Design-Tokens-and-Atoms?node-id=945-299977&t=0ECasAESMUX0VzkW-4


    
> [!Notes]
> This is a notes and I have to make it a notes
---

### 2. **Context & Problem Statement**

- What is IQL? (brief about product domain: multi-tenant, healthcare SaaS)
    
- Why did you need a design system?
    
    - Inconsistencies across modules (e.g. EMR, Lab, IPD, etc.)
        
    - Developer handoffs taking time
        
    - Difficulty in applying branding for different clients
        
- State the **goals** of the system
    
    - Consistency
        
    - Theming for different organizations
        
    - Developer efficiency
        
    - Accessibility & Scalability
        

---

### 3. **Team & Collaboration**

- Your role and key responsibilities
- Who else was involved?
    - Devs, QA, PMs
- How did you collaborate?
    - Weekly syncs, design tokens discussions, Git workflows

---

### 4. **Foundation*
- **Research / Audits**
    - UI inventory across products
    - Identifying patterns & inconsistencies
- **Decisions**
    - Chose px over rem for legacy reasons
    - Token groups: Base, Semantic, Theme, Responsive
    - Token syncing via Figma plugin → GitHub → CI/CD

---

### 5. **Design Token Strategy**

- Token structure:
    |Group|Purpose|Examples|
    |---|---|---|
    |Base|Raw values|`#000000`, `14px`, `24px`|
    |Semantic|Meaningful use|`text.primary`, `bg.surface`|
    |Theme|Brand-specific overrides|`primary.main`, `accent.alt`|
    |Responsive|Breakpoint-specific tokens|`fontSize.sm`, `padding.md`|
    
- How you handled:
    - **Light/Dark modes**
    - **Multi-brand theming**
    - **Tailwind conversion**
    
![[IQL Design System.png]]

---

### 6. **Component Library**

- Built using React + Tailwind (or Chakra UI?)
    
- List key components:
    
    - Button, Input, Modal, Toast, Badge, etc.
        
- States and variants (primary, secondary, disabled, loading)
    
- How tokens power these components
    
- Developer documentation + Storybook (if used)
    

---

### 7. **CI/CD & Dev Integration**

- Setup for:
    
    - Figma → Tokens Plugin → GitHub → Style Dictionary → NPM Package
        
- Challenges and learnings from GitHub PAT permissions, file structure, etc.
    
- Platform-based output: Web, Mobile, Tailwind, etc.
    

---

### 8. **Adoption & Impact**

- Metrics (if available):
    
    - No. of products using it
        
    - Speed of dev implementation
        
    - Consistency improvement
        
- Testimonials from devs or PMs
    
- Before & After Screenshots
    

---

### 9. **Challenges & Learnings**

- Token management edge cases
    
- Collaborating across multiple product teams
    
- Keeping it modular and scalable
    
- Dealing with legacy CSS overrides
    

---

### 10. **What’s Next / Roadmap**

- Token Studio → Figma Variables migration?
    
- Theming Admin Panel for organizations
    
- Accessibility Audits
    
- Cross-platform tokens (Flutter, React Native?)
    

---

### 11. **Final Reflection**

- Personal growth as a system thinker
    
- How this project sharpened your collaboration and scalability skills
    
- Your design philosophy that guided this work
    

---

## 💡 Bonus Tips for Portfolio:

- Include interactive snippets (if it's on a site)
    
- Use side-by-side before-after comparisons
    
- Add mini-gifs showing tokens being applied
    
- Keep it scannable and visually clean
    
- End with a CTA like “Reach out if you want to talk design systems!”