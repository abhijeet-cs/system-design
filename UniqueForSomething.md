## 🔗 Given an input string, unique short string can be generated via below approaches

### 1. Use characters from user input ⚠️ (Weakest)
- Predictable  
- High collision  
### 2. Hash input → Base62 🔐
- Collision possible  
- Lookup required  
### 3. Random number → Base62 🎲
- Collision possible  
- Lookup required  
### 4. Counter / auto-increment → Base62 ✅ (Best)
- Guaranteed unique  
- Distributed counters could be complex  
