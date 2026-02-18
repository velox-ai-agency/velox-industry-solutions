# Test Cases - Real Estate Solution

## 🔹 Test Case 1: Property Inquiry

| Field | Value |
|-------|-------|
| **ID** | TC-RE-001 |
| **Name** | Property Inquiry Flow |
| **Priority** | High |

### Pre-conditions
- AI Receptionist is active
- Evolution API connected
- Test property in database

### Test Steps
1. Send WhatsApp message: "أريد معرفة تفاصيل شقة في المهندسين"
2. Verify AI responds within 30 seconds
3. Check property details are sent
4. Verify lead is saved to Google Sheets

### Expected Result
- [ ] Response received < 30s
- [ ] Property details correct
- [ ] Lead saved with correct info
- [ ] Follow-up scheduled

---

## 🔹 Test Case 2: Appointment Booking

| Field | Value |
|-------|-------|
| **ID** | TC-RE-002 |
| **Name** | Schedule Property Visit |
| **Priority** | High |

### Test Steps
1. Request appointment: "أريد حجز معاينة بكرة الساعة 5"
2. Verify available slots shown
3. Confirm booking
4. Check Google Calendar event created
5. Verify confirmation message sent

### Expected Result
- [ ] Available slots shown
- [ ] Calendar event created
- [ ] Confirmation sent
- [ ] Reminder scheduled

---

## 🔹 Test Case 3: After Hours Call

| Field | Value |
|-------|-------|
| **ID** | TC-RE-003 |
| **Name** | After Hours Handling |
| **Priority** | Medium |

### Test Steps
1. Call outside business hours (e.g., 11 PM)
2. Verify greeting message
3. Leave inquiry
4. Check callback scheduled for next day

### Expected Result
- [ ] Greeting played
- [ ] Inquiry recorded
- [ ] Callback scheduled
- [ ] Lead created

---

## 🔹 Test Case 4: Lead Qualification

| Field | Value |
|-------|-------|
| **ID** | TC-RE-004 |
| **Name** | Lead Scoring |
| **Priority** | High |

### Test Steps
1. Start conversation with various budgets
2. Verify lead score calculated
3. Check high-priority leads flagged
4. Verify agent notification sent

### Expected Result
- [ ] Budget captured
- [ ] Score calculated correctly
- [ ] High-value leads flagged
- [ ] Agent notified

---

## 🔹 Test Case 5: Multi-language Support

| Field | Value |
|-------|-------|
| **ID** | TC-RE-005 |
| **Name** | Bilingual Conversation |
| **Priority** | Medium |

### Test Steps
1. Send message in Arabic
2. Verify Arabic response
3. Switch to English
4. Verify English response
5. Check language consistency

### Expected Result
- [ ] Arabic response correct
- [ ] English response correct
- [ ] Language detected automatically
- [ ] No mixed language responses
