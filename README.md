# Agentic AI ภาษาไทย — Lab notebooks สำหรับผู้เรียน

Notebook ประกอบคลิป YouTube ชุด *Agentic AI ภาษาไทย* อิงจากตำรา *The Hitchhiker's Guide to Agentic AI* (Haggai Roitman, CC BY-SA 4.0)

แต่ละ lab มี 2 ไฟล์

- **✏️ Starter** — โค้ดส่วนใหญ่เตรียมไว้แล้ว ดูคลิปแล้วเติมเฉพาะจุด `✏️ TODO` ทุกจุดบอกเวลาในคลิปที่อธิบายโค้ดตรงนั้น
- **✅ เฉลย** — โค้ดชุดเดียวกับในคลิป รันได้ทันที ใช้เทียบเมื่อติด

## เริ่มต้น

1. กดปุ่ม **Open in Colab** ของ lab ที่ต้องการ (หรือดาวน์โหลด `.ipynb` ไปเปิดใน Jupyter บนเครื่อง)
2. สมัคร API key ที่ [openrouter.ai](https://openrouter.ai) → Keys → Create Key
3. **Colab:** ไอคอน 🔑 Secrets → เพิ่ม `OPENROUTER_API_KEY` → เปิด *Notebook access*  
   **เครื่องตัวเอง:** สร้างไฟล์ `.env` ข้าง notebook ใส่ `OPENROUTER_API_KEY=sk-or-...`
4. รันทุก cell จากบนลงล่าง

⚠️ อย่าใส่ key ลงในโค้ดโดยตรง และอย่า commit ไฟล์ `.env`

## 19.2 Autonomous Agent Patterns

| Lab | ✏️ Starter | ✅ เฉลย |
|---|---|---|
| Lab 1 — ReAct Loop | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/VRU-AI-SWU/agentic-ai-students/blob/main/ch19/19-2/lab1-react.student.ipynb) · [ไฟล์](ch19/19-2/lab1-react.student.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/VRU-AI-SWU/agentic-ai-students/blob/main/ch19/19-2/lab1-react.ipynb) · [ไฟล์](ch19/19-2/lab1-react.ipynb) |
| Lab 2 — Planning Agent | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/VRU-AI-SWU/agentic-ai-students/blob/main/ch19/19-2/lab2-planning.student.ipynb) · [ไฟล์](ch19/19-2/lab2-planning.student.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/VRU-AI-SWU/agentic-ai-students/blob/main/ch19/19-2/lab2-planning.ipynb) · [ไฟล์](ch19/19-2/lab2-planning.ipynb) |
| Lab 3 — Reflexion | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/VRU-AI-SWU/agentic-ai-students/blob/main/ch19/19-2/lab3-reflexion.student.ipynb) · [ไฟล์](ch19/19-2/lab3-reflexion.student.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/VRU-AI-SWU/agentic-ai-students/blob/main/ch19/19-2/lab3-reflexion.ipynb) · [ไฟล์](ch19/19-2/lab3-reflexion.ipynb) |
| Lab 4 — Tool-Use Patterns | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/VRU-AI-SWU/agentic-ai-students/blob/main/ch19/19-2/lab4-tool-use.student.ipynb) · [ไฟล์](ch19/19-2/lab4-tool-use.student.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/VRU-AI-SWU/agentic-ai-students/blob/main/ch19/19-2/lab4-tool-use.ipynb) · [ไฟล์](ch19/19-2/lab4-tool-use.ipynb) |

## License

Notebook ทั้งหมดดัดแปลงจาก Haggai Roitman, *The Hitchhiker's Guide to Agentic AI: From Foundations to Systems* ([arXiv:2606.24937](https://arxiv.org/abs/2606.24937)) และเผยแพร่ภายใต้ [CC BY-SA 4.0](LICENSE) ข้อมูลใน tools เป็นข้อมูลจำลองเพื่อการสอน
