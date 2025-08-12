# Task 6 – Create a Strong Password and Evaluate Its Strength

## Objective
Understand what makes a password strong and test it against password strength tools.

---

## Steps Followed

1. **Create multiple passwords with varying complexity.**  
   Examples:
   - `apple123` (weak)
   - `ApplE2025` (medium)
   - `A@pple2025` (strong)
   - `B@sk3t_C@se_91!` (very strong)
   - `Pine^Forest!29River#` (very strong)

2. **Use uppercase, lowercase, numbers, symbols, and length variations.**  
   This ensures a better mix of characters and reduces predictability.

3. **Test each password on a password strength checker.**  
   Tool used: [Password Meter](https://passwordmeter.com)

4. **Note scores and feedback from the tool.**  
   Screenshots of results are attached below.

---

## Password Strength Table

| Password                  | Score (%) | Strength Level  | Feedback Highlights                                      |
|---------------------------|-----------|-----------------|----------------------------------------------------------|
| `apple123`                | 38%       | Weak            | Too short, lacks symbols and uppercase letters.          |
| `ApplE2025`               | 58%       | Medium          | Better length, needs symbols for extra security.         |
| `A@pple2025`              | 97%       | Strong          | Good mix, could increase length for max security.        |
| `B@sk3t_C@se_91!`         | 100%      | Very Strong     | Excellent mix of all character types.                    |
| `Pine^Forest!29River#`    | 100%      | Very Strong     | Ideal: long, random, and complex.                        |

---

## Password Strength Test Results

### Weak Password Example – `apple123`
<img width="800" height="500" alt="weak_pass" src="https://github.com/user-attachments/assets/04b6362e-5f96-4102-a937-3e79232cfb62" />

- **Score:** 38%  
- **Complexity:** Weak  
- **Issues:** No uppercase letters, no symbols, short length.

---

### Strong Password Example – `A@pple2025`
<img width="800" height="500" alt="Strong_pass" src="https://github.com/user-attachments/assets/38656d2a-a533-4394-9de9-9b47964a0f4f" />

- **Score:** 97%  
- **Complexity:** Very Strong  
- **Strengths:** Includes uppercase, lowercase, numbers, symbols, and sufficient length.

---

## Color Indicator Legend
<img width="800" height="200" alt="color_indicator" src="https://github.com/user-attachments/assets/123e017f-0b82-425c-a080-2471ab85d389" />

- **Exceptional:** Exceeds minimum standards.  
- **Sufficient:** Meets minimum standards.  
- **Warning:** Advisory against bad practices.  
- **Failure:** Does not meet minimum standards.

---

## Best Practices for Creating Strong Passwords

1. Use **at least 12–16 characters**.
2. Include **uppercase, lowercase, numbers, and symbols**.
3. Avoid dictionary words or personal information.
4. Use **random combinations** or passphrases.
5. Change passwords regularly.
6. Use a **password manager** for unique passwords per account.

---

## Tips Learned from Evaluation

- Adding symbols and numbers greatly improves strength.
- Avoid sequential characters and repeated patterns.
- Longer passwords are harder to crack.
- Mixing all character types boosts security score.

---

## Common Password Attacks

### 1. Brute Force Attack
- **Method:** The attacker tries every possible combination of characters until the correct password is found.  
- **Time Impact:** The more characters and complexity, the longer it takes to crack.  
- **Example:** A 6-character lowercase password can be cracked in seconds; a 16-character mixed password can take centuries.

### 2. Dictionary Attack
- **Method:** Uses a precompiled list of common words, leaked passwords, and common phrases.  
- **Weakness:** Easily cracks passwords that are simple words (e.g., `football`, `password123`).  
- **Defense:** Avoid dictionary words; add complexity and randomness.

### 3. Hybrid Attack
- **Method:** Combines dictionary attacks with slight variations, such as replacing letters with numbers (`password` → `p@ssw0rd`).  
- **Defense:** Avoid predictable substitutions and patterns.

### 4. Credential Stuffing
- **Method:** Uses stolen username/password pairs from data breaches to log into multiple sites.  
- **Defense:** Use unique passwords for each account and enable MFA.

### 5. Phishing
- **Method:** Tricks users into entering credentials into fake websites or forms.  
- **Defense:** Always verify URLs, use password managers to auto-fill only on real sites.

---

## How Password Complexity Affects Security

- **Short + Simple:** Easy to guess or crack quickly.
- **Long + Random:** Exponentially harder to break.
- Example:  
  - 8-char lowercase only → cracked in hours.  
  - 16-char with mixed types → could take centuries to crack.  

Complexity increases **entropy** (randomness), making passwords far less predictable.

---
