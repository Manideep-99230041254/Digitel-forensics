# Experiment 04: Email Header Analysis & Spoofing Detection

## Objective
To analyze email headers and detect possible spoofing using Mail Header Analyzer (MHA).

## Tools Used
- Mail Header Analyzer (MHA)
- 
- <img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/8dc11484-a580-4bea-97d1-791fa1833164" />

- Email Clients (Gmail, Outlook, Yahoo)
- MXToolbox / G Suite Toolbox
  
- <img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/3cc46f54-ae39-41c6-97a4-0228eb7ae449" />
<img width="1864" height="906" alt="Image" src="https://github.com/user-attachments/assets/8f21c6d3-85a2-4c86-b216-682fbdb269bb" />
<img width="1228" height="711" alt="Image" src="https://github.com/user-attachments/assets/a8abf577-2a46-4380-adf2-d052b8db460a" />
<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/0ba27092-2cc9-474a-97ab-324ee97e60ee" />



## Procedure
1. **Access Header**:
   - Gmail → More (⋮) → Show original
   - <img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/279b745e-55e9-4b25-b040-1348e6c9df2a" />

   - Outlook → File → Properties → Internet headers
   - Yahoo → More (⋮) → View raw message
2. **Copy Header Text** → Extract metadata.

 <img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/71741f3b-551d-45d3-a09d-3957f20f9780" />
<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/cd457841-0384-4adb-8875-46e19aceb8ef" />

4. **Analyze Key Fields**:
   - From / To / Return-Path / Message-ID
   - Received (trace server hops)
   - SPF / DKIM / DMARC (authentication)
5. **Check Received Fields**:
   - Verify hops in reverse order.
   - Detect mismatched IPs/hosts.
   -   -  <img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/085d301d-e28a-440b-b5c6-38c81937bbe7" />

    - <img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/e16914ea-59c2-4a9c-977d-3bc05f03ffc0" />
<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/3258d5f7-dc2f-484e-8587-acf1106d703f" />
<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/d50e3a6a-1d28-44b1-8969-e0ed1582a2e0" />
<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/6c116385-5188-4dce-9578-3e2ec37fab66" />
<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/a7ee4609-42a8-45b8-9fee-4564813bf3dc" />
<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/4af63113-4e7c-4ef1-9c90-f8681edd37df" />
<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/7388e89b-c420-4728-bcf7-5d0c8c4e96c8" />
<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/141d752e-db55-4c1b-98b1-cef0d6767bd3" />
<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/c497caa2-9804-4d93-ae6d-0098cf85404b" />
<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/a4220fc9-48e4-4ce8-a65d-f08222257aed" />
<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/4acb5f5d-3b6d-4518-adf6-375d02beb081" />
<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/7b580c7f-d097-4bb5-ae25-f58e101fe60c" />
<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/fd1b35ec-36f0-4db1-b6d0-43b7337d24b2" />
<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/79a1c887-6b11-4d09-813b-d48b451983dc" />
<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/f416cdad-9e48-44e4-b6d9-1f65d88c7bc9" />
<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/d7701ceb-4bf5-47b3-adfa-269389ea2595" />
<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/58e8e05b-2331-4c19-bc99-2570b49967e0" />
  
6. **Authentication Checks**:
   - SPF → Authorized sending server
   - DKIM → Content integrity
   - DMARC → Alignment check
7. **Look for Anomalies**:
   - Domain mismatches
   - Suspicious IPs
   - Timestamp gaps
8. **Use Tools**: MXToolbox / G Suite Toolbox for automated analysis.

---

## Result
- Extracted and analyzed headers with MHA.
- Identified anomalies in SPF/DKIM/DMARC.
- Logged suspicious IPs and mismatched domains.

## Conclusion
Email header analysis is critical for detecting spoofing and phishing by verifying server hops and authentication records.
