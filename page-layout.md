# PDP Page Layout Specification

## Page Structure

```
PdpPage (Root Container)
├── Headerbase
├── Frame13 (Breadcrumb Container)
└── Frame3 (Main Content)
    ├── ProductMediaSection
    └── Frame6 (Product Details)
```

---

## Component Layout Details

### **PdpPage** (Root Container)
- **Background**: `color.bg.secondary`
- **Layout**: Flex column
- **Gap**: `Spacing.m`
- **Alignment**: Center
- **Width**: `100%`
- **Height**: `100%`

---

### **Headerbase**
- **Background**: `color.bg.primary`
- **Padding**: 
  - Horizontal: `Spacing.4xl`
  - Vertical: `Spacing.2xl`
- **Width**: `100%`
- **Layout**: Flex row
- **Alignment**: Space between, items center

#### **Frame** (Navigation Menu)
- **Gap**: `Spacing.2xl`
- **Layout**: Flex row
- **Alignment**: Items center

##### **Menu, Menu1, Menu2**
- **Font Size**: `fontSize.Body`
- **Font Family**: `fontFamily.body`
- **Font Weight**: `fontWeight.body`
- **Color**: `color.text.primary`

#### **Frame2** (Action Icons Container)
- **Gap**: `Spacing.xl`
- **Layout**: Flex row
- **Alignment**: Items center

##### **Frame1** (Icon Wrapper)
- **Height**: `Spacing.2xl`

###### **Container** (Icon Container)
- **Border Radius**: `borderRadius.button`
- **Size**: `Spacing.2xl`

###### **Icon** (Search Icon)
- **Size**: `fontSize.H5`
- **Stroke**: `color.text.primary`

---

### **Frame13** (Breadcrumb Container)
- **Width**: `Grid.11 Column` or `100%`
- **Layout**: Flex column
- **Alignment**: Items start

#### **Breadcrumbs**
- **Padding**:
  - Horizontal: `Spacing.xs`
  - Vertical: `Spacing.m`
- **Gap**: `Spacing.xl`
- **Font Size**: `fontSize.XS`
- **Font Family**: `fontFamily.body`
- **Font Weight**: `fontWeight.body`
- **Color**: `color.text.secondary`
- **Layout**: Flex row
- **Alignment**: Items center, justify center

---

### **Frame3** (Main Content Container)
- **Padding**:
  - Horizontal: `Spacing.4xl`
  - Vertical: `Spacing.xs`
- **Gap**: `Spacing.2xl`
- **Layout**: Flex row
- **Alignment**: Items start
- **Width**: `100%`

---

## Primary Region

### **ProductMediaSection**
- **Width**: `Grid.8 Column`
- **Gap**: `Spacing.m`
- **Layout**: Flex column
- **Alignment**: Items start

#### **Main Product Image**
- **Height**: `552px`
- **Width**: `100%`
- **Border Radius**: `Spacing.m` or `borderRadius.card`

#### **Frame4** (Thumbnail Container)
- **Gap**: `Spacing.m`
- **Height**: `184px`
- **Width**: `100%`
- **Layout**: Flex row
- **Alignment**: Items start

##### **Rectangle, Rectangle1** (Thumbnails)
- **Border Radius**: `borderRadius.button`
- **Border**: `1px solid color.text.primary`
- **Height**: `184px`
- **Flex**: `1 0 0`

---

## Secondary Region

### **Frame6** (Product Details Container)
- **Width**: `Grid.4 Column`
- **Gap**: `Spacing.3xl`
- **Layout**: Flex column
- **Alignment**: Items start

---

#### **Productbrandrating**
- **Width**: `Grid.5 Column`
- **Gap**: `Spacing.xl`
- **Layout**: Flex column
- **Alignment**: Items start

##### **Frame5** (Brand & Favorite)
- **Width**: `100%`
- **Layout**: Flex row
- **Alignment**: Items start, justify space between

###### **Brand Name Text**
- **Font Size**: `fontSize.XS`
- **Font Family**: `fontFamily.body`
- **Font Weight**: `fontWeight.body`
- **Color**: `color.text.primary`

###### **Heart** (Favorite Icon)
- **Size**: `Spacing.2xl`
- **Fill**: `color.text.primary`

##### **StarRating**
- **Gap**: `Spacing.m` (original: 6px, nearest token)
- **Layout**: Flex row
- **Alignment**: Items center

###### **Vector** (Star Icon)
- **Size**: `Spacing.xl`
- **Fill**: `color.brand.primary`

###### **Rating Count Text**
- **Font Size**: `fontSize.Body`
- **Font Family**: `fontFamily.body`
- **Font Weight**: `fontWeight.body`
- **Color**: `color.text.primary`

---

#### **Product Name Text**
- **Font Size**: `fontSize.H2`
- **Font Family**: `fontFamily.body`
- **Font Weight**: `fontWeight.body`
- **Color**: `color.text.primary`
- **Width**: `100%`

---

#### **ProductPrice**
- **Height**: `fontSize.H2`
- **Width**: `353px`

##### **Frame7** (Price Container)
- **Gap**: `Spacing.xl`
- **Layout**: Flex row
- **Alignment**: Items center
- **Font Family**: `fontFamily.body`
- **Font Weight**: `fontWeight.body`
- **Color**: `color.text.primary`

###### **Current Price**
- **Font Size**: `fontSize.H2`

###### **Original Price**
- **Font Size**: `fontSize.H4`
- **Text Decoration**: Strikethrough

###### **Discount Percentage**
- **Font Size**: `fontSize.H4`

---

#### **SizeColorSelector**
- **Width**: `100%`
- **Gap**: `Spacing.2xl`
- **Layout**: Flex column
- **Alignment**: Items start

##### **Size Chart Link**
- **Font Size**: `fontSize.Body`
- **Font Family**: `fontFamily.body`
- **Font Weight**: `fontWeight.body`
- **Color**: `color.text.primary`
- **Text Decoration**: Underline
- **Width**: `100%`

##### **Frame8** (Selector Container)
- **Gap**: `Spacing.xl`
- **Width**: `100%`
- **Layout**: Flex row
- **Alignment**: Items center

###### **Dropdown, Dropdown1** (Size/Color Selectors)
- **Background**: `color.bg.tertiary`
- **Border Radius**: `Spacing.3xl` or `borderRadius.card`
- **Padding**:
  - Horizontal: `Spacing.xl`
  - Vertical: `Spacing.lg`
- **Layout**: Flex row
- **Alignment**: Items center, justify space between
- **Flex**: `1 0 0`

**Label Text**:
- **Font Size**: `fontSize.Body`
- **Font Family**: `fontFamily.body`
- **Font Weight**: `fontWeight.body`
- **Color**: `color.text.primary`

**ChevronDown Icon**:
- **Size**: `Spacing.2xl`
- **Fill**: `color.text.primary`

---

#### **Available Options Label**
- **Font Size**: `fontSize.Body`
- **Font Family**: `fontFamily.body`
- **Font Weight**: `fontWeight.body`
- **Color**: `color.text.primary`
- **Width**: `100%`

---

#### **Frame11** (Purchase Options Container)
- **Gap**: `Spacing.xl`
- **Layout**: Flex row
- **Alignment**: Items start

##### **CardSelector, CardSelector1** (Option Cards)
- **Background**: `color.bg.tertiary`
- **Border**: `1px solid color.text.primary`
- **Border Radius**: `Spacing.4xl` or `borderRadius.card`
- **Padding**: `Spacing.xl`
- **Gap**: `Spacing.lg`
- **Width**: `130px`
- **Layout**: Flex column
- **Alignment**: Items start

###### **Frame9, Frame10** (Icon Wrapper)
- **Background**: `color.text.primary`
- **Border Radius**: `Spacing.4xl` or `borderRadius.card`
- **Padding**: `Spacing.m`

**Dollar Icon**:
- **Size**: `Spacing.2xl`
- **Fill**: `color.bg.primary`

###### **"To order" Text**
- **Font Size**: `fontSize.SM`
- **Font Family**: `fontFamily.body`
- **Font Weight**: `fontWeight.body`
- **Color**: `color.text.primary`
- **Width**: `100%`

###### **Price Text**
- **Font Size**: `fontSize.H5`
- **Font Family**: `fontFamily.body`
- **Font Weight**: `fontWeight.heading`
- **Color**: `color.text.primary`
- **Width**: `100%`

---

#### **Frame12** (Delivery Info Container)
- **Gap**: `Spacing.xl`
- **Layout**: Flex column
- **Alignment**: Items start

##### **Iconwithtext** (Delivery Info Item)
- **Gap**: `Spacing.m`
- **Layout**: Flex row
- **Alignment**: Items center

###### **Truck** (Icon)
- **Size**: `Spacing.2xl`
- **Fill**: `color.text.primary`

###### **Delivery Text**
- **Font Size**: `fontSize.SM`
- **Font Family**: `fontFamily.body`
- **Font Weight**: `fontWeight.body`
- **Color**: `color.text.primary`

---

#### **Button** (CTA)
- **Background**: `color.brand.primary`
- **Border Radius**: `Spacing.3xl` or `borderRadius.card`
- **Padding**:
  - Horizontal: `Spacing.lg`
  - Vertical: `Spacing.xl`
- **Width**: `100%`
- **Layout**: Flex row
- **Alignment**: Items center, justify center

##### **Button Text**
- **Font Size**: `fontSize.SM`
- **Font Family**: `fontFamily.body`
- **Font Weight**: `fontWeight.body`
- **Color**: `color.bg.primary`