# 2024-ITCS431-Gemini9

## Actors and Their Roles

### 1. **Astronomers**

**Functional Requirements:**
- Must be able to create science plans, including defining observation goals and configurations.
- Must be able to test science plans using a virtual telescope environment.
- Must be able to submit validated science plans for execution.
- Must be able to monitor observations in real-time, either remotely or on-site.
- Must be able to collect, validate, and ensure the integrity of astronomical data.
- Must be able to retrieve archived observational data efficiently.
- Must be able to send instructions or updates to science observers during observation sessions.

**Non-Functional Requirements:**
- Interfaces must be intuitive and user-friendly, minimizing the learning curve.
- Access must be restricted to roles (e.g., no telescope control privileges).
- Data integrity must be ensured during transmission and archival, with mechanisms to prevent loss or corruption.
- Remote monitoring tools must perform reliably even with limited bandwidth.

---

### 2. **Science Observers**

**Functional Requirements:**
- Must be able to validate science plans and transform them into observing programs.
- Must be able to execute observing programs, including managing instruments and telescope alignment.
- Must be able to monitor real-time observation progress and make adjustments as needed.
- Must be able to prioritize or reschedule queued observations dynamically based on conditions like weather or urgent science goals.

**Non-Functional Requirements:**
- Monitoring tools must display real-time updates with minimal latency.
- Interfaces must support rapid decision-making with clear visualizations of instrument and telescope status.
- System performance must allow for dynamic queue adjustments without disrupting ongoing observations.

---

### 3. **Telescope Operators**

**Functional Requirements:**
- Must be able to control the telescope and its instruments.
- Must be able to manage system startup and shutdown procedures.
- Must be able to monitor the system’s operational integrity and respond to faults promptly.
- Must be able to perform manual overrides when necessary to ensure observation safety.

**Non-Functional Requirements:**
- Telescope control systems must respond to commands within milliseconds to prevent delays during observations.
- Interfaces must provide clear error messages and troubleshooting guidance.
- Safety measures must prevent unintended commands from affecting telescope operations.

---

### 4. **Support Staff**

**Functional Requirements:**
- Must be able to perform routine maintenance on hardware and software systems.
- Must be able to validate and install configurations for subsystems.
- Must be able to assist with integrating third-party instruments and devices.

**Non-Functional Requirements:**
- Maintenance tools must ensure compatibility with the existing system while providing rollback options for failed updates.
- The system must log all maintenance activities for traceability.
- Interfaces must include diagnostic tools for troubleshooting subsystem issues.

---

### 5. **Developers**

**Functional Requirements:**
- Must be able to design, test, and deploy subsystem enhancements.
- Must be able to perform integration testing for new features.
- Must be able to access detailed system logs and performance metrics.

**Non-Functional Requirements:**
- Development tools must support simulation environments to test changes without affecting live operations.
- Subsystem updates must maintain backward compatibility with the existing system.
- Deployment processes must minimize downtime and provide clear rollback mechanisms.

---

### 6. **Administrators**

**Functional Requirements:**
- Must be able to manage user roles, permissions, and access levels.
- Must be able to oversee system scheduling and allocate observation time slots.
- Must be able to handle high-level system inquiries and ensure smooth collaboration between user groups.

**Non-Functional Requirements:**
- Administrative tools must offer robust security features to prevent unauthorized access.
- Scheduling systems must optimize telescope utilization and minimize idle time.
- Interfaces must provide detailed reports and analytics to assist in decision-making.

---


