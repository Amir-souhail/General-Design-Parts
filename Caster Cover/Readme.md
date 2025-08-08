
# **Reverse-Engineered Caster Cover - SolidWorks 2025**

## **🔍 Project Origin**
- **Source**: Publicly available caster cover design (original drawings provided in `/original_drawings`).  
- **Redesign Goal**: Improved manufacturability and parametric flexibility in SolidWorks 2025.  

## **🔄 Reverse Engineering Highlights**
1. **Key Improvements**:  
   - Added **configurable Design Table** for keyway sizes (5-12mm axles).  
   - Optimized **0.2mm fillets** for 3D printing/CNC.  
   - Threaded holes (**M4/M5**) for secure assembly.  

2. **SolidWorks 2025 Features Used**:  
   - `Defeature` tool to simplify legacy geometry.  
   - `TolAnalyst` for ISO 2768-mK tolerance validation.  

## **📐 Key Specs**
- **File Formats**:  
  - `.SLDPRT` (Parametric) | `.STEP` (Multi-CAD) | `.PDF` (2D Drawing).  
- **Materials**:  
  - **Steel**: `SW Material Library > AISI 304`.  
  - **Nylon**: `SW Plastics > Nylon 6/6`.  

## **🛠️ Usage**
```markdown
1. Open `caster_cover.SLDPRT` in SolidWorks 2025+.  
2. Adjust dimensions via `Design Table` (included).  
3. Export `.STEP` for CNC or `.STL` for 3D printing.  
```

## **⚠️ Disclaimer**
- Original design sourced from public domain.  
- Reverse-engineered model provided **AS-IS** for educational purposes.  



