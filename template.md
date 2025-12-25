# <Paper Title>

**Authors:**  
**Year:**  
**Link:**  
**Area:** Inference | Systems | Compiler | Runtime | Energy | Economics  
**Read Status:** skimmed | deep read | replicated | extended  

---

## 1. One-Sentence Thesis
> What is the single most important idea of this paper?

---

## 2. Problem / Bottleneck
**What concrete bottleneck does this paper address?**

- [ ] Memory bandwidth
- [ ] KV-cache management
- [ ] Kernel launch overhead
- [ ] Scheduling / batching
- [ ] Tail latency (p95 / p99)
- [ ] Energy / power
- [ ] Cost efficiency
- [ ] Other: ___________________

---

## 3. Key Insight (Plain English)
Explain the core idea as if to a systems engineer in 60 seconds.  
No equations. No jargon.

---

## 4. Where the Leverage Comes From
**Primary leverage:**
- [ ] Algorithmic
- [ ] Scheduling
- [ ] Compiler
- [ ] Runtime
- [ ] Hardware-aware
- [ ] Economic / cost-aware

**Secondary leverage (if any):**
- ______________________________________

---

## 5. System Model
**What does the system actually look like?**

- Execution model (static / dynamic / hybrid)
- Hardware assumptions (GPU / CPU / accelerator)
- Workload assumptions (batch size, sequence length, traffic shape)

Optional sketch / diagram:

## 6. Assumptions
**List all assumptions this work relies on.**

## 7. What Breaks at Scale or in Production?
**Be adversarial.**

- Multi-tenant interference?
- Bursty or adversarial traffic?
- SLA / tail latency constraints?
- Memory pressure or fragmentation?
- Heterogeneous hardware?

## 8. Results that Actually Mattter
**Ignore vanity metrics.**

- Latency (p50 / p95 / p99):
- Throughput:
- Memory usage:
- Energy / joules (if reported):
- Accuracy impact:

## 9. Inference Economics Impact
**How does this change the economics?**

- Cost per request:
- Cost per token:
- Energy per token:
- Capacity utilization:
- Marginal scaling cost:

## 10. Connection(s)
**Explicitly link this paper to what you’re building.**

## 11. One Concrete Experiment to Run
**If you had one week, what would you test?**

## 12. Open Questions / Research Extensions
**What did this paper not solve?**

## 13. Personal Take
**Will this:**
- Age well?
- Become infrastructure?
- Be replaced by something simpler?
Why?

## 14. Tags
#inference #systems #scheduling #compiler #runtime #energy #economics