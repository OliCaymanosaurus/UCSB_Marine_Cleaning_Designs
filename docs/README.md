# Documentation

## 🌊 Background

Oceanographic instruments that measure pH, chlorophyll, and other marine parameters are highly vulnerable to marine growth, which can disrupt data accuracy.  

Currently, two divers are required every two weeks to manually clean these sensors using bleach. The standard method — carrying syringes of bleach in a bag — has proven to be cumbersome, as the syringes often float away and are difficult to keep track of underwater.

---

## 🧪 Syringe Holder Prototypes

### **V1: Initial Design**
- 3D printed circular holder with 7 holes for syringes and a dozen smaller holes for zip ties.
- **Issue:** Cold water caused the syringes to shrink and escape the holder. Divers had to hold the contraption sideways to prevent the syringes from floating out.

---

### **V2: Tighter Fit**
- Increased capacity to 10 syringe slots with smaller holes for a tighter fit and better retention.
- **Issue:** Syringes still floated out in cold water. Overlapping syringe tabs led to jamming in the center.

---

### **V3: Tapered Fit**
- Fixed spacing of holes.
- Tapered holes drafted inward for a tighter fit at the bottom, while still allowing easy insertion.
- **Issue:** Circular shape was awkward to hold underwater. Required a second diver to hold while dispensing bleach.

---

### **V4: Linear Handle Design**
- Shifted to a linear shape with a handle.
- Can be set directly on the instrument caging.
- **Result:** Reduced cleaning time, allowing the task to be performed by a single diver.

---

## ⚙️ Automation Concepts

### Existing Setup
The instruments already use periodic **air blasts** to reduce buildup, but still require bleach treatments every two weeks.

---

### **Proposed Solution: Integrated Bleach Dosing**
We are testing a **passive bleach delivery system** that leverages the existing air pathway:
- **Mechanism:** Solid bleach capsules are placed within a segment of tubing connected to the air line.
- Each air pulse partially dissolves a capsule, pushing bleach-laced water into the instrument.
- As water naturally refills the tubing after the blast, the next air cycle continues dissolving the capsule incrementally.

---

### System Details
- The air pump turns on once every 24 hours.
- Total: 8 air blasts.
- The first 7 blasts: ~1 second each.
- The final blast: ~10 seconds.
- This cycle pushes air through the reservoir, including the stagnant water, and flows it through the CTD plumbing.

> **Note:** It remains unclear if the CTD pump can also pull some of the reservoir water into the CTD plumbing.

---

## 📌 Summary

These prototypes and automation efforts aim to reduce diver time, improve safety, and maintain high-quality instrument readings over long-term deployments.

---

