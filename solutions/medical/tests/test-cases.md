# Test Cases - Medical Clinics Solution

## 🔹 Test Case 1: Appointment Booking

| Field | Value |
|-------|-------|
| **ID** | TC-MC-001 |
| **Name** | Book New Appointment |
| **Priority** | High |

### Test Steps
1. Send WhatsApp: "أريد حجز موعد مع دكتور أحمد"
2. Select specialty from list
3. Choose available date/time
4. Confirm booking
5. Verify confirmation sent
6. Check calendar event created

### Expected Result
- [ ] Specialty selection shown
- [ ] Available slots displayed
- [ ] Booking confirmed
- [ ] Calendar event created
- [ ] Confirmation message sent

---

## 🔹 Test Case 2: Appointment Reminder

| Field | Value |
|-------|-------|
| **ID** | TC-MC-002 |
| **Name** | Automated Reminder |
| **Priority** | High |

### Test Steps
1. Create appointment for tomorrow
2. Wait for reminder trigger (24h before)
3. Verify reminder sent
4. Patient confirms attendance
5. Check status updated

### Expected Result
- [ ] Reminder sent 24h before
- [ ] Confirmation link included
- [ ] Status updated correctly
- [ ] Clinic notified of confirmation

---

## 🔹 Test Case 3: Patient Intake

| Field | Value |
|-------|-------|
| **ID** | TC-MC-003 |
| **Name** | New Patient Registration |
| **Priority** | High |

### Test Steps
1. New patient initiates conversation
2. Request intake form
3. Fill required fields
4. Submit form
5. Verify patient record created

### Expected Result
- [ ] Intake form sent
- [ ] All required fields validated
- [ ] Patient record created
- [ ] Appointment booking offered

---

## 🔹 Test Case 4: Insurance Verification

| Field | Value |
|-------|-------|
| **ID** | TC-MC-004 |
| **Name** | Insurance Check |
| **Priority** | Medium |

### Test Steps
1. Patient provides insurance info
2. System checks coverage
3. Display covered services
4. Calculate patient responsibility
5. Confirm understanding

### Expected Result
- [ ] Insurance verified
- [ ] Coverage displayed
- [ ] Cost estimate provided
- [ ] Consent recorded

---

## 🔹 Test Case 5: Emergency Triage

| Field | Value |
|-------|-------|
| **ID** | TC-MC-005 |
| **Name** | Emergency Handling |
| **Priority** | Critical |

### Test Steps
1. Patient reports emergency symptoms
2. AI detects emergency keywords
3. Immediate escalation triggered
4. Emergency contact provided
5. Follow-up scheduled

### Expected Result
- [ ] Emergency detected
- [ ] Escalation triggered
- [ ] Emergency number provided
- [ ] Log created
