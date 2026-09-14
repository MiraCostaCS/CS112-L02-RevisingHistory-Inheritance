## 📋 Project Assessment: Lab 02 - Revising History + Inheritance
---

### 1. Git & Workflow
- [ ] **Commit Messages:** Descriptive and incremental (e.g., "Implemented deep copy in HistoricalEvent constructor").

### 2. Functional Requirements
- [ ] **HistoricalEvent (Base Class):**
    - [ ] **Constructors:** full, default, and copy constructors implemented
    - [ ] **Encapsulation:** Private instance variables, each with their own Getters/Setters.
    - [ ] **Deep Copying:** Implemented in constructors and getters/setters for mutable objects (Date).
    - [ ] **toString():** Overridden with `@Override` with all event details.
    - [ ] **equals():** Overridden with `@Override` to compare instance variable values, not references. Should check for null and use introspection
- [ ] **RevisedHistoricalEvent (Subclass):**
    - [ ] **Inheritance:** Correctly uses `extends HistoricalEvent`.
    - [ ] **Constructors:** Uses `super()` to initialize parent instance variables and set new ones
    - [ ] **teach():** Specific method logic implemented as described in prompt.
    - [ ] **Standard Overrides:** `toString()` and `equals()` include parent data (using `super`).
    - [ ] **Encapsulation:** same required model methods (setters/getters, constructors, etc.)
- [ ] **Driver Program (Main.java):**
    - [ ] **New Historical Event:** Instantiates a `RevisedHistoricalEvent` with new/different description, date, revised description, and citation

### 3. Code Quality & Standards
- [ ] **OOP Standards:**
    - [ ] Instance variables are `private`.
    - [ ] **Strategic Deep Copying:** Applied where it makes the most sense to protect data integrity (hint: where you get/set the `Date` object)
- [ ] **Reusability:** Reusing setters/setAll in constructors
- [ ] **Error Checking:** Checking for errors in constructors and handling if present (shutdown program)
- [ ] **Annotations:** `@Override` flag used correctly above all overridden methods.
- [ ] **Naming Conventions:** `camelCase` for methods/variables; `PascalCase` for classes.
- [ ] **Formatting:** Consistent indentation and clear code structure.
- [ ] **Constants:** Create constants as needed for easier to read code and reusability, at the very least for default data.
- [ ] **Curly Braces:** Single-line blocks should use curly braces, even if compiler does not require it.
- [ ] **Documentation:** Every method, except `@Override` flagged ones, should be fully documented. Ideally with JavaDoc syntax. Class-level description and class-invariant as well

