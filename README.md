# indian-bank-logos

An open source collection of high-quality logos for all active banks in India — public sector, private sector, small finance banks, payments banks, foreign banks, and neo banks.

Maintained for use in fintech apps, dashboards, and any project that needs reliable Indian bank branding assets.

---

## CDN Usage

All logos are served via jsDelivr and are available immediately after any commit.

**SVG (recommended — crisp at any size)**
```
https://cdn.jsdelivr.net/gh/keyushhh/indian-bank-logos@main/logos/{slug}.svg
```

**PNG**
```
https://cdn.jsdelivr.net/gh/keyushhh/indian-bank-logos@main/logos/{slug}.png
```

**Example**
```
https://cdn.jsdelivr.net/gh/keyushhh/indian-bank-logos@main/logos/hdfc.svg
https://cdn.jsdelivr.net/gh/keyushhh/indian-bank-logos@main/logos/sbi.png
```

---

## Usage in Code

**React**
```tsx
const CDN = "https://cdn.jsdelivr.net/gh/keyushhh/indian-bank-logos@main/logos";

<img src={`${CDN}/hdfc.svg`} alt="HDFC Bank" width={120} />
```

**HTML**
```html
<img src="https://cdn.jsdelivr.net/gh/keyushhh/indian-bank-logos@main/logos/sbi.svg" alt="SBI" width="120" />
```

---

## Folder Structure

All files live in a single flat `logos/` folder. No subfolders.

```
logos/
  sbi.svg
  sbi.png
  hdfc.svg
  hdfc.png
  icici.svg
  icici.png
  ...
```

---

## Bank List

### Public Sector Banks (12)

| Bank Name | Slug | Formats |
|---|---|---|
| State Bank of India | `sbi` | SVG, PNG |
| Punjab National Bank | `pnb` | SVG, PNG |
| Bank of Baroda | `bob` | SVG, PNG |
| Bank of India | `boi` | SVG, PNG |
| Canara Bank | `canara` | SVG, PNG |
| Union Bank of India | `union` | SVG, PNG |
| Bank of Maharashtra | `bom` | SVG, PNG |
| Indian Bank | `indian-bank` | SVG, PNG |
| Central Bank of India | `central-bank` | SVG, PNG |
| Indian Overseas Bank | `iob` | SVG, PNG |
| UCO Bank | `uco` | SVG, PNG |
| Punjab & Sind Bank | `psb` | SVG, PNG |

### Private Sector Banks (23)

| Bank Name | Slug | Formats |
|---|---|---|
| HDFC Bank | `hdfc` | SVG, PNG |
| ICICI Bank | `icici` | SVG, PNG |
| Axis Bank | `axis` | SVG, PNG |
| Kotak Mahindra Bank | `kotak` | SVG, PNG |
| IndusInd Bank | `indusind` | SVG, PNG |
| Yes Bank | `yes` | SVG, PNG |
| IDFC FIRST Bank | `idfc` | SVG, PNG |
| Federal Bank | `federal` | SVG, PNG |
| Bandhan Bank | `bandhan` | SVG, PNG |
| RBL Bank | `rbl` | SVG, PNG |
| South Indian Bank | `sib` | SVG, PNG |
| Karur Vysya Bank | `kvb` | SVG, PNG |
| City Union Bank | `cub` | SVG, PNG |
| Catholic Syrian Bank | `csb` | SVG, PNG |
| DCB Bank | `dcb` | SVG, PNG |
| J&K Bank | `jkb` | SVG, PNG |
| Karnataka Bank | `karnataka` | SVG, PNG |
| Tamilnad Mercantile Bank | `tmb` | SVG, PNG |
| Dhanlaxmi Bank | `dhanlaxmi` | SVG, PNG |
| IDBI Bank | `idbi` | SVG, PNG |
| Nainital Bank | `nainital` | PNG |
| SVC Bank | `svc` | PNG |
| Saraswat Bank | `saraswat` | SVG, PNG |

### Small Finance Banks (12)

| Bank Name | Slug | Formats |
|---|---|---|
| AU Small Finance Bank | `au` | SVG, PNG |
| Equitas Small Finance Bank | `equitas` | SVG, PNG |
| Ujjivan Small Finance Bank | `ujjivan` | SVG, PNG |
| Jana Small Finance Bank | `jana` | SVG, PNG |
| ESAF Small Finance Bank | `esaf` | PNG |
| Suryoday Small Finance Bank | `suryoday` | PNG |
| Capital Small Finance Bank | `capital-sfb` | PNG |
| North East Small Finance Bank | `nesfb` | PNG |
| Shivalik Small Finance Bank | `shivalik` | PNG |
| Unity Small Finance Bank | `unity` | PNG |
| Utkarsh Small Finance Bank | `utkarsh` | SVG, PNG |
| SBFC Small Finance Bank | `sbfc` | PNG |

### Payments Banks (4)

| Bank Name | Slug | Formats |
|---|---|---|
| Airtel Payments Bank | `airtel` | SVG, PNG |
| India Post Payments Bank | `ippb` | SVG, PNG |
| Fino Payments Bank | `fino` | PNG |
| Jio Payments Bank | `jio` | SVG, PNG |

> Paytm Payments Bank is excluded — its licence was cancelled by the RBI in March 2024.

### Foreign Banks (5)

| Bank Name | Slug | Formats |
|---|---|---|
| HSBC India | `hsbc` | SVG, PNG |
| Standard Chartered India | `sc` | SVG, PNG |
| DBS Bank India | `dbs` | SVG, PNG |
| Citibank India | `citi` | SVG, PNG |
| Deutsche Bank India | `deutsche` | SVG, PNG |

### Neo Banks (4)

| Bank Name | Slug | Formats |
|---|---|---|
| Slice | `slice` | PNG |
| Fi Money | `fi` | PNG |
| Jupiter | `jupiter` | PNG |
| Niyo | `niyo` | PNG |

> Neo banks are not independent banks. They operate on top of licensed banking partners. Slice merged with North East Small Finance Bank in 2024.

---

## Contributing

Contributions are welcome. If a bank logo is missing, incorrect, or outdated, please open a pull request.

**Guidelines**

- File names must be lowercase with hyphens, matching the slug in the table above
- Submit both SVG and PNG where possible
- SVG files should be clean vectors, not embedded bitmaps
- PNG files should be a minimum of 300px on the longest side
- Source logos from official bank websites or Wikimedia Commons only
- Do not submit logos with watermarks, drop shadows, or white background boxes

**To add a missing bank**

1. Fork this repository
2. Add your logo files to the `logos/` folder following the naming convention
3. Update this README with the new entry in the correct category table
4. Open a pull request with a brief description of the source

---

## License

Logo files belong to their respective banks and are used here for identification purposes only. This repository does not claim ownership of any bank branding. Use responsibly and in accordance with each institution's brand guidelines.
