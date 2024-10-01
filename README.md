# AWS SES and SNS Pricing Structure

## AWS Simple Email Service (SES)

### Emails Sent:
- **Free Tier:** 62,000 emails/month are free if sent from an Amazon EC2 instance.
- **Pay-As-You-Go:**
  - $0.10 for every 1,000 emails sent.

### Emails Received:
- **Free Tier:** The first 1,000 incoming emails per month are free.
- **Pay-As-You-Go:**
  - $0.10 for every 1,000 emails received.

### Additional Charges for Attachments (Email Content):
- $0.12 per GB of email content.

### Dedicated IPs (Optional):
- $24.95 per dedicated IP address per month.

---

## AWS Simple Notification Service (SNS)

### SNS for SMS:
- **Free Tier:**
  - 100 SMS messages/month for free.

- **Pay-As-You-Go (Example Pricing):**
  - **US (Transactional):** $0.0075 per SMS.
  - **India (Transactional):** $0.0024 per SMS.
  
  - **Note:** Prices vary by country. Check specific rates for different regions [here](https://aws.amazon.com/sns/sms-pricing/).

### SNS for Email Notifications:
- **Emails Sent:**
  - $0.50 per 1 million requests, in addition to the SES email-sending price.

### SNS for Application and HTTP/HTTPS Notifications:
- **Free Tier:**
  - 1 million requests/month.

- **Pay-As-You-Go:**
  - $0.50 per 1 million publish requests.

### Other Notifications:
- **Mobile Push Notifications:** Free.
- **SNS Topics:** No additional charge for creating and subscribing to topics.

---

For detailed pricing information for specific regions and services, visit:
- [AWS SES Pricing](https://aws.amazon.com/ses/pricing/)
- [AWS SNS Pricing](https://aws.amazon.com/sns/pricing/)
