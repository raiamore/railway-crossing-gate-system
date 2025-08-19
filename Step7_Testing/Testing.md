# Step 7 – Testing and Refinement

## Test Cases

| Case | Train Approaching | Vehicle on Track | Expected Output                  | Result |
|------|------------------|------------------|----------------------------------|--------|
| 1    | Yes              | No               | Gates down, alarm on             | Pass   |
| 2    | No               | Yes              | Gates down, alarm on             | Pass   |
| 3    | Yes              | Yes              | Gates down, alarm on             | Pass   |
| 4    | No               | No               | Gates up (after 3s delay), alarm off | Pass   |

---

## Refinements

- Add dual train sensors for redundancy.  
- Integrate a manual override for emergency staff control.  
- Introduce a short buffer time (3–5s) before raising gates to ensure late vehicles are detected.  
- Incorporate CCTV for monitoring and verification.  
