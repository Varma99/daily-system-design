## ✅ What is Consistency?

When multiple clients access a system, **consistency** ensures that they all see the **same data** — no matter who accesses it or from where.

If one client updates data, others should immediately see that update.

---

## 🔁 Why is Consistency Important?

- Prevents confusion between users
- Ensures data correctness
- Avoids double booking, duplicate actions, or stale reads

---

## 🔄 Example

In the **BookMyShow app**, when a seat is booked by one user, it should immediately become unavailable to others. That’s high consistency.

---

## 🏗️ High vs Low Consistency

| System Type     | Consistency Level | Notes                                      |
|------------------|--------------------|---------------------------------------------|
| Monolithic       | High               | Single DB → easier to keep consistent       |
| Distributed      | Low (by default)   | Replicas take time to sync (eventual consistency) |

---

## ⚠️ Where Consistency Breaks

- In **distributed systems**, due to:
  - Replication delays
  - Network partitions
  - Conflicting writes on different nodes

---

## 🚀 How to Improve Consistency

- Use **strong consistency** models (e.g., quorum reads/writes)
- Use centralized locking or leader election
- Design with **eventual consistency** in mind and handle conflict resolution

---

## 📝 Summary

- Consistency = All clients see the same data.
- Strong in centralized systems.
- Harder to maintain in distributed systems.
