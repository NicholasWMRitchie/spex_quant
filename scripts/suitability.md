
C:\Users\nritchie\Documents\repositories\spex_quant\scripts>rem foreach(z->println("spex suitable "EDAX All" $(symbol(element(z))) $(symbol(element(z))) 20 --format markdown"),1:99) 

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" Be Be 20 --format markdown 
| Region            | Result | Coating | Notes |
|-------------------|--------|---------|-------|
| [Be K-L₁; 1.0000> | Ok     | Ok      |       |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" B B 20 --format markdown 
| Region           | Result | Coating | Notes |
|------------------|--------|---------|-------|
| [B K-L₂; 1.0000> | Ok     | Ok      |       |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" BN B 20 --format markdown 
| Region           | Result     | Coating | Notes                                    |
|------------------|------------|---------|------------------------------------------|
| [B K-L₂; 1.0000> | Interfered | Ok      | [N K-L₂ and 1 others; 1.0000> on [27,51) |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" C C 20 --format markdown 
| Region                        | Result | Coating | Notes |
|-------------------------------|--------|---------|-------|
| [C K-L₃ and 1 others; 1.0000> | Ok     | Ok      |       |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>rem spex suitable "EDAX All" O O 20 --format markdown 

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" BN N 20 --format markdown 
| Region                        | Result     | Coating | Notes                       |
|-------------------------------|------------|---------|-----------------------------|
| [N K-L₂ and 1 others; 1.0000> | Interfered | Ok      | [B K-L₂; 1.0000> on [10,29) |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" AlN N 20 --format markdown 
| Region                        | Result | Coating | Notes |
|-------------------------------|--------|---------|-------|
| [N K-L₂ and 1 others; 1.0000> | Ok     | Ok      |       |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" TiN N 20 --format markdown 
| Region                        | Result     | Coating | Notes                               |
|-------------------------------|------------|---------|-------------------------------------|
| [N K-L₂ and 1 others; 1.0000> | Interfered | Ok      | [Ti L₃-M₁ and 13 others; 0.9693> on |
|                               |            |         | [29,63)                             |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" Si3N4 N 20 --format markdown 
| Region                        | Result | Coating | Notes |
|-------------------------------|--------|---------|-------|
| [N K-L₂ and 1 others; 1.0000> | Ok     | Ok      |       |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" CaF2 F 20 --format markdown 
| Region                        | Result | Coating | Notes |
|-------------------------------|--------|---------|-------|
| [F K-L₂ and 1 others; 1.0000> | Ok     | Ok      |       |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" LiF F 20 --format markdown 
| Region                        | Result | Coating | Notes |
|-------------------------------|--------|---------|-------|
| [F K-L₂ and 1 others; 1.0000> | Ok     | Ok      |       |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>rem spex suitable "EDAX All" Ne Ne 20 --format markdown 

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" NaF Na 20 --format markdown 
| Region                          | Result | Coating | Notes |
|---------------------------------|--------|---------|-------|
| [Na L₁-L₂ and 1 others; 1.0000> | Ok     | Ok      |       |
| [Na K-L₂ and 1 others; 1.0000>  | Ok     | Ok      |       |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" NaAlSi3O8 Na 20 --format markdown 
| Region                          | Result     | Coating | Notes                              |
|---------------------------------|------------|---------|------------------------------------|
| [Na L₁-L₂ and 1 others; 1.0000> | Interfered | Ok      | [Al L₁-L₂ and 5 others; 1.0000> on |
|                                 |            |         | [10,17), [Si L₁-L₂ and 5 others;   |
|                                 |            |         | 1.0000> on [10,21)                 |
| [Na K-L₂ and 1 others; 1.0000>  | Ok         | Ok      |                                    |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" NaCl Na 20 --format markdown 
| Region                          | Result     | Coating | Notes                              |
|---------------------------------|------------|---------|------------------------------------|
| [Na L₁-L₂ and 1 others; 1.0000> | Interfered | Ok      | [Cl L₁-L₂ and 8 others; 1.0000> on |
|                                 |            |         | [10,36)                            |
| [Na K-L₂ and 1 others; 1.0000>  | Ok         | Ok      |                                    |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" Na3AlF6 Na 20 --format markdown 
| Region                          | Result     | Coating | Notes                              |
|---------------------------------|------------|---------|------------------------------------|
| [Na L₁-L₂ and 1 others; 1.0000> | Interfered | Ok      | [Al L₁-L₂ and 5 others; 1.0000> on |
|                                 |            |         | [10,17)                            |
| [Na K-L₂ and 1 others; 1.0000>  | Ok         | Ok      |                                    |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" Mg Mg 20 --format markdown 
| Region                          | Result | Coating | Notes |
|---------------------------------|--------|---------|-------|
| [Mg L₁-L₂ and 2 others; 1.0000> | Ok     | Ok      |       |
| [Mg K-L₂ and 1 others; 1.0000>  | Ok     | Ok      |       |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" MgO Mg 20 --format markdown 
| Region                          | Result | Coating | Notes |
|---------------------------------|--------|---------|-------|
| [Mg L₁-L₂ and 2 others; 1.0000> | Ok     | Ok      |       |
| [Mg K-L₂ and 1 others; 1.0000>  | Ok     | Ok      |       |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" Al Al 20 --format markdown 
| Region                          | Result | Coating | Notes |
|---------------------------------|--------|---------|-------|
| [Al L₁-L₂ and 5 others; 1.0000> | Ok     | Ok      |       |
| [Al K-L₂ and 3 others; 1.0000>  | Ok     | Ok      |       |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" Al2O3 Al 20 --format markdown 
| Region                          | Result | Coating | Notes |
|---------------------------------|--------|---------|-------|
| [Al L₁-L₂ and 5 others; 1.0000> | Ok     | Ok      |       |
| [Al K-L₂ and 3 others; 1.0000>  | Ok     | Ok      |       |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" AlN Al 20 --format markdown 
| Region                          | Result | Coating | Notes |
|---------------------------------|--------|---------|-------|
| [Al L₁-L₂ and 5 others; 1.0000> | Ok     | Ok      |       |
| [Al K-L₂ and 3 others; 1.0000>  | Ok     | Ok      |       |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" Si Si 20 --format markdown 
| Region                          | Result | Coating | Notes |
|---------------------------------|--------|---------|-------|
| [Si L₁-L₂ and 5 others; 1.0000> | Ok     | Ok      |       |
| [Si K-L₂ and 3 others; 1.0000>  | Ok     | Ok      |       |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" SiO2 Si 20 --format markdown 
| Region                          | Result | Coating | Notes |
|---------------------------------|--------|---------|-------|
| [Si L₁-L₂ and 5 others; 1.0000> | Ok     | Ok      |       |
| [Si K-L₂ and 3 others; 1.0000>  | Ok     | Ok      |       |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" Si3N4 Si 20 --format markdown 
| Region                          | Result | Coating | Notes |
|---------------------------------|--------|---------|-------|
| [Si L₁-L₂ and 5 others; 1.0000> | Ok     | Ok      |       |
| [Si K-L₂ and 3 others; 1.0000>  | Ok     | Ok      |       |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" GaP P 20 --format markdown 
| Region                         | Result     | Coating | Notes                               |
|--------------------------------|------------|---------|-------------------------------------|
| [P L₁-L₂ and 6 others; 1.0000> | Interfered | Ok      | [Ga M₁-M₂ and 10 others; 1.0010> on |
|                                |            |         | [10,24)                             |
| [P K-L₂ and 3 others; 1.0000>  | Ok         | Ok      |                                     |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" Fe2P Fe 20 --format markdown 
| Region                           | Result     | Coating | Notes                             |
|----------------------------------|------------|---------|-----------------------------------|
| [Fe M₁-M₂ and 8 others; 1.0045>  | Interfered | Ok      | [P L₁-L₂ and 6 others; 1.0000> on |
|                                  |            |         | [10,27)                           |
| [Fe L₃-M₁ and 13 others; 0.9955> | Ok         | Ok      |                                   |
| [Fe K-L₂ and 1 others; 0.8923>   | Ok         | Ok      |                                   |
| [Fe K-M₂ and 1 others; 0.1077>   | Ok         | Ok      |                                   |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" FeS2 S 20 --format markdown 
| Region                         | Result     | Coating | Notes                              |
|--------------------------------|------------|---------|------------------------------------|
| [S L₁-L₂ and 7 others; 1.0000> | Interfered | Ok      | [Fe M₁-M₂ and 8 others; 1.0045> on |
|                                |            |         | [10,21)                            |
| [S K-L₂ and 3 others; 1.0000>  | Ok         | Ok      |                                    |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" NaCl Cl 20 --format markdown 
| Region                          | Result     | Coating | Notes                              |
|---------------------------------|------------|---------|------------------------------------|
| [Cl L₁-L₂ and 8 others; 1.0000> | Interfered | Ok      | [Na L₁-L₂ and 1 others; 1.0000> on |
|                                 |            |         | [10,13)                            |
| [Cl K-L₂ and 3 others; 1.0000>  | Ok         | Ok      |                                    |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" KCl Cl 20 --format markdown 
| Region                          | Result     | Coating | Notes                              |
|---------------------------------|------------|---------|------------------------------------|
| [Cl L₁-L₂ and 8 others; 1.0000> | Interfered | Ok      | [K L₁-L₂ and 10 others; 1.0000> on |
|                                 |            |         | [10,46)                            |
| [Cl K-L₂ and 3 others; 1.0000>  | Ok         | Ok      |                                    |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" BaCl Cl 20 --format markdown 
| Region                          | Result     | Coating | Notes                               |
|---------------------------------|------------|---------|-------------------------------------|
| [Cl L₁-L₂ and 8 others; 1.0000> | Interfered | Ok      | [Ba N₁-N₂ and 17 others; 1.0237> on |
|                                 |            |         | [10,42)                             |
| [Cl K-L₂ and 3 others; 1.0000>  | Ok         | Ok      |                                     |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>rem spex suitable "EDAX All" Ar Ar 20 --format markdown 

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" KCl K 20 --format markdown 
| Region                          | Result     | Coating | Notes                              |
|---------------------------------|------------|---------|------------------------------------|
| [K L₁-L₂ and 10 others; 1.0000> | Interfered | Ok      | [Cl L₁-L₂ and 8 others; 1.0000> on |
|                                 |            |         | [10,36)                            |
| [K K-L₂ and 3 others; 1.0000>   | Ok         | Ok      |                                    |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" CaF2 Ca 20 --format markdown 
| Region                           | Result | Coating | Notes |
|----------------------------------|--------|---------|-------|
| [Ca L₁-L₂ and 10 others; 1.0000> | Ok     | Ok      |       |
| [Ca K-L₂ and 3 others; 1.0000>   | Ok     | Ok      |       |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" Sc Sc 20 --format markdown 
| Region                           | Result | Coating | Notes |
|----------------------------------|--------|---------|-------|
| [Sc M₁-M₂ and 3 others; 1.0531>  | Ok     | Ok      |       |
| [Sc L₃-M₁ and 12 others; 0.9469> | Ok     | Ok      |       |
| [Sc K-L₂ and 3 others; 1.0000>   | Ok     | Ok      |       |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" Ti Ti 20 --format markdown 
| Region                           | Result | Coating | Notes |
|----------------------------------|--------|---------|-------|
| [Ti M₁-M₂ and 5 others; 1.0269>  | Ok     | Ok      |       |
| [Ti L₃-M₁ and 13 others; 0.9693> | Ok     | Ok      |       |
| [Ti K-L₂ and 3 others; 1.0000>   | Ok     | Ok      |       |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" TiO2 Ti 20 --format markdown 
| Region                           | Result     | Coating | Notes                            |
|----------------------------------|------------|---------|----------------------------------|
| [Ti M₁-M₂ and 5 others; 1.0269>  | Ok         | Ok      |                                  |
| [Ti L₃-M₁ and 13 others; 0.9693> | Interfered | Ok      | [O K-L₂ and 1 others; 1.0000> on |
|                                  |            |         | [40,64)                          |
| [Ti K-L₂ and 3 others; 1.0000>   | Ok         | Ok      |                                  |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" TiS2 Ti 20 --format markdown 
| Region                           | Result     | Coating | Notes                             |
|----------------------------------|------------|---------|-----------------------------------|
| [Ti M₁-M₂ and 5 others; 1.0269>  | Interfered | Ok      | [S L₁-L₂ and 7 others; 1.0000> on |
|                                  |            |         | [10,31)                           |
| [Ti L₃-M₁ and 13 others; 0.9693> | Interfered | Ok      | [S L₁-L₂ and 7 others; 1.0000> on |
|                                  |            |         | [10,31)                           |
| [Ti K-L₂ and 3 others; 1.0000>   | Ok         | Ok      |                                   |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" TiC Ti 20 --format markdown 
| Region                           | Result     | Coating | Notes                            |
|----------------------------------|------------|---------|----------------------------------|
| [Ti M₁-M₂ and 5 others; 1.0269>  | Interfered | Ok      | [C K-L₃ and 1 others; 1.0000> on |
|                                  |            |         | [15,38)                          |
| [Ti L₃-M₁ and 13 others; 0.9693> | Interfered | Ok      | [C K-L₃ and 1 others; 1.0000> on |
|                                  |            |         | [15,38)                          |
| [Ti K-L₂ and 3 others; 1.0000>   | Ok         | Ok      |                                  |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" TiN Ti 20 --format markdown 
| Region                           | Result     | Coating | Notes                            |
|----------------------------------|------------|---------|----------------------------------|
| [Ti M₁-M₂ and 5 others; 1.0269>  | Ok         | Ok      |                                  |
| [Ti L₃-M₁ and 13 others; 0.9693> | Interfered | Ok      | [N K-L₂ and 1 others; 1.0000> on |
|                                  |            |         | [27,51)                          |
| [Ti K-L₂ and 3 others; 1.0000>   | Ok         | Ok      |                                  |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" V V 20 --format markdown 
| Region                          | Result | Coating | Notes |
|---------------------------------|--------|---------|-------|
| [V M₁-M₂ and 7 others; 1.0114>  | Ok     | Ok      |       |
| [V L₃-M₁ and 13 others; 0.9842> | Ok     | Ok      |       |
| [V K-L₂ and 1 others; 0.8960>   | Ok     | Ok      |       |
| [V K-M₂ and 1 others; 0.1040>   | Ok     | Ok      |       |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" V2O5 V 20 --format markdown 
| Region                          | Result     | Coating | Notes                            |
|---------------------------------|------------|---------|----------------------------------|
| [V M₁-M₂ and 7 others; 1.0114>  | Ok         | Ok      |                                  |
| [V L₃-M₁ and 13 others; 0.9842> | Interfered | Ok      | [O K-L₂ and 1 others; 1.0000> on |
|                                 |            |         | [40,64)                          |
| [V K-L₂ and 1 others; 0.8960>   | Ok         | Ok      |                                  |
| [V K-M₂ and 1 others; 0.1040>   | Ok         | Ok      |                                  |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" VC V 20 --format markdown 
| Region                          | Result     | Coating | Notes                            |
|---------------------------------|------------|---------|----------------------------------|
| [V M₁-M₂ and 7 others; 1.0114>  | Interfered | Ok      | [C K-L₃ and 1 others; 1.0000> on |
|                                 |            |         | [15,38)                          |
| [V L₃-M₁ and 13 others; 0.9842> | Interfered | Ok      | [C K-L₃ and 1 others; 1.0000> on |
|                                 |            |         | [15,38)                          |
| [V K-L₂ and 1 others; 0.8960>   | Ok         | Ok      |                                  |
| [V K-M₂ and 1 others; 0.1040>   | Ok         | Ok      |                                  |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" Cr Cr 20 --format markdown 
| Region                           | Result | Coating | Notes |
|----------------------------------|--------|---------|-------|
| [Cr M₁-M₂ and 8 others; 1.0098>  | Ok     | Ok      |       |
| [Cr L₃-M₁ and 13 others; 0.9902> | Ok     | Ok      |       |
| [Cr K-L₂ and 1 others; 0.8966>   | Ok     | Ok      |       |
| [Cr K-M₂ and 1 others; 0.1033>   | Ok     | Ok      |       |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" CrN Cr 20 --format markdown 
| Region                           | Result     | Coating | Notes                            |
|----------------------------------|------------|---------|----------------------------------|
| [Cr M₁-M₂ and 8 others; 1.0098>  | Ok         | Ok      |                                  |
| [Cr L₃-M₁ and 13 others; 0.9902> | Interfered | Ok      | [N K-L₂ and 1 others; 1.0000> on |
|                                  |            |         | [27,51)                          |
| [Cr K-L₂ and 1 others; 0.8966>   | Ok         | Ok      |                                  |
| [Cr K-M₂ and 1 others; 0.1033>   | Ok         | Ok      |                                  |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" Cr3C2 Cr 20 --format markdown 
| Region                           | Result     | Coating | Notes                            |
|----------------------------------|------------|---------|----------------------------------|
| [Cr M₁-M₂ and 8 others; 1.0098>  | Interfered | Ok      | [C K-L₃ and 1 others; 1.0000> on |
|                                  |            |         | [15,38)                          |
| [Cr L₃-M₁ and 13 others; 0.9902> | Ok         | Ok      |                                  |
| [Cr K-L₂ and 1 others; 0.8966>   | Ok         | Ok      |                                  |
| [Cr K-M₂ and 1 others; 0.1033>   | Ok         | Ok      |                                  |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" Mn Mn 20 --format markdown 
| Region                           | Result | Coating | Notes |
|----------------------------------|--------|---------|-------|
| [Mn M₁-M₂ and 8 others; 1.0063>  | Ok     | Ok      |       |
| [Mn L₃-M₁ and 13 others; 0.9937> | Ok     | Ok      |       |
| [Mn K-L₂ and 1 others; 0.8933>   | Ok     | Ok      |       |
| [Mn K-M₂ and 1 others; 0.1067>   | Ok     | Ok      |       |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" MnCO3 Mn 20 --format markdown 
| Region                           | Result     | Coating | Notes                            |
|----------------------------------|------------|---------|----------------------------------|
| [Mn M₁-M₂ and 8 others; 1.0063>  | Interfered | Ok      | [C K-L₃ and 1 others; 1.0000> on |
|                                  |            |         | [15,38)                          |
| [Mn L₃-M₁ and 13 others; 0.9937> | Interfered | Ok      | [O K-L₂ and 1 others; 1.0000> on |
|                                  |            |         | [40,64)                          |
| [Mn K-L₂ and 1 others; 0.8933>   | Ok         | Ok      |                                  |
| [Mn K-M₂ and 1 others; 0.1067>   | Ok         | Ok      |                                  |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" MnF2 Mn 20 --format markdown 
| Region                           | Result     | Coating | Notes                            |
|----------------------------------|------------|---------|----------------------------------|
| [Mn M₁-M₂ and 8 others; 1.0063>  | Ok         | Ok      |                                  |
| [Mn L₃-M₁ and 13 others; 0.9937> | Interfered | Ok      | [F K-L₂ and 1 others; 1.0000> on |
|                                  |            |         | [54,80)                          |
| [Mn K-L₂ and 1 others; 0.8933>   | Ok         | Ok      |                                  |
| [Mn K-M₂ and 1 others; 0.1067>   | Ok         | Ok      |                                  |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" MnS Mn 20 --format markdown 
| Region                           | Result     | Coating | Notes                             |
|----------------------------------|------------|---------|-----------------------------------|
| [Mn M₁-M₂ and 8 others; 1.0063>  | Interfered | Ok      | [S L₁-L₂ and 7 others; 1.0000> on |
|                                  |            |         | [10,31)                           |
| [Mn L₃-M₁ and 13 others; 0.9937> | Ok         | Ok      |                                   |
| [Mn K-L₂ and 1 others; 0.8933>   | Ok         | Ok      |                                   |
| [Mn K-M₂ and 1 others; 0.1067>   | Ok         | Ok      |                                   |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" MnTiO3 Mn 20 --format markdown 
| Region                           | Result     | Coating | Notes                              |
|----------------------------------|------------|---------|------------------------------------|
| [Mn M₁-M₂ and 8 others; 1.0063>  | Interfered | Ok      | [Ti M₁-M₂ and 5 others; 1.0269> on |
|                                  |            |         | [10,19)                            |
| [Mn L₃-M₁ and 13 others; 0.9937> | Interfered | Ok      | [O K-L₂ and 1 others; 1.0000> on   |
|                                  |            |         | [40,64), [Ti L₃-M₁ and 13 others;  |
|                                  |            |         | 0.9693> on [29,63)                 |
| [Mn K-L₂ and 1 others; 0.8933>   | Ok         | Ok      |                                    |
| [Mn K-M₂ and 1 others; 0.1067>   | Ok         | Ok      |                                    |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" MnO2 Mn 20 --format markdown 
| Region                           | Result     | Coating | Notes                            |
|----------------------------------|------------|---------|----------------------------------|
| [Mn M₁-M₂ and 8 others; 1.0063>  | Ok         | Ok      |                                  |
| [Mn L₃-M₁ and 13 others; 0.9937> | Interfered | Ok      | [O K-L₂ and 1 others; 1.0000> on |
|                                  |            |         | [40,64)                          |
| [Mn K-L₂ and 1 others; 0.8933>   | Ok         | Ok      |                                  |
| [Mn K-M₂ and 1 others; 0.1067>   | Ok         | Ok      |                                  |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" Fe Fe 20 --format markdown 
| Region                           | Result | Coating | Notes |
|----------------------------------|--------|---------|-------|
| [Fe M₁-M₂ and 8 others; 1.0045>  | Ok     | Ok      |       |
| [Fe L₃-M₁ and 13 others; 0.9955> | Ok     | Ok      |       |
| [Fe K-L₂ and 1 others; 0.8923>   | Ok     | Ok      |       |
| [Fe K-M₂ and 1 others; 0.1077>   | Ok     | Ok      |       |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" FeS2 Fe 20 --format markdown 
| Region                           | Result     | Coating | Notes                             |
|----------------------------------|------------|---------|-----------------------------------|
| [Fe M₁-M₂ and 8 others; 1.0045>  | Interfered | Ok      | [S L₁-L₂ and 7 others; 1.0000> on |
|                                  |            |         | [10,31)                           |
| [Fe L₃-M₁ and 13 others; 0.9955> | Ok         | Ok      |                                   |
| [Fe K-L₂ and 1 others; 0.8923>   | Ok         | Ok      |                                   |
| [Fe K-M₂ and 1 others; 0.1077>   | Ok         | Ok      |                                   |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" FeO Fe 20 --format markdown 
| Region                           | Result     | Coating | Notes                            |
|----------------------------------|------------|---------|----------------------------------|
| [Fe M₁-M₂ and 8 others; 1.0045>  | Ok         | Ok      |                                  |
| [Fe L₃-M₁ and 13 others; 0.9955> | Interfered | Ok      | [O K-L₂ and 1 others; 1.0000> on |
|                                  |            |         | [40,64)                          |
| [Fe K-L₂ and 1 others; 0.8923>   | Ok         | Ok      |                                  |
| [Fe K-M₂ and 1 others; 0.1077>   | Ok         | Ok      |                                  |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" Fe2O3 Fe 20 --format markdown 
| Region                           | Result     | Coating | Notes                            |
|----------------------------------|------------|---------|----------------------------------|
| [Fe M₁-M₂ and 8 others; 1.0045>  | Ok         | Ok      |                                  |
| [Fe L₃-M₁ and 13 others; 0.9955> | Interfered | Ok      | [O K-L₂ and 1 others; 1.0000> on |
|                                  |            |         | [40,64)                          |
| [Fe K-L₂ and 1 others; 0.8923>   | Ok         | Ok      |                                  |
| [Fe K-M₂ and 1 others; 0.1077>   | Ok         | Ok      |                                  |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" Fe2P Fe 20 --format markdown 
| Region                           | Result     | Coating | Notes                             |
|----------------------------------|------------|---------|-----------------------------------|
| [Fe M₁-M₂ and 8 others; 1.0045>  | Interfered | Ok      | [P L₁-L₂ and 6 others; 1.0000> on |
|                                  |            |         | [10,27)                           |
| [Fe L₃-M₁ and 13 others; 0.9955> | Ok         | Ok      |                                   |
| [Fe K-L₂ and 1 others; 0.8923>   | Ok         | Ok      |                                   |
| [Fe K-M₂ and 1 others; 0.1077>   | Ok         | Ok      |                                   |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" FeSi2 Fe 20 --format markdown 
| Region                           | Result     | Coating | Notes                              |
|----------------------------------|------------|---------|------------------------------------|
| [Fe M₁-M₂ and 8 others; 1.0045>  | Interfered | Ok      | [Si L₁-L₂ and 5 others; 1.0000> on |
|                                  |            |         | [10,21)                            |
| [Fe L₃-M₁ and 13 others; 0.9955> | Ok         | Ok      |                                    |
| [Fe K-L₂ and 1 others; 0.8923>   | Ok         | Ok      |                                    |
| [Fe K-M₂ and 1 others; 0.1077>   | Ok         | Ok      |                                    |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" Co Co 20 --format markdown 
| Region                           | Result | Coating | Notes |
|----------------------------------|--------|---------|-------|
| [Co M₁-M₂ and 8 others; 1.0033>  | Ok     | Ok      |       |
| [Co L₃-M₁ and 13 others; 0.9967> | Ok     | Ok      |       |
| [Co K-L₂ and 1 others; 0.8914>   | Ok     | Ok      |       |
| [Co K-M₂ and 2 others; 0.1086>   | Ok     | Ok      |       |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" Co3O4 Co 20 --format markdown 
| Region                           | Result     | Coating | Notes                            |
|----------------------------------|------------|---------|----------------------------------|
| [Co M₁-M₂ and 8 others; 1.0033>  | Ok         | Ok      |                                  |
| [Co L₃-M₁ and 13 others; 0.9967> | Interfered | Ok      | [O K-L₂ and 1 others; 1.0000> on |
|                                  |            |         | [40,64)                          |
| [Co K-L₂ and 1 others; 0.8914>   | Ok         | Ok      |                                  |
| [Co K-M₂ and 2 others; 0.1086>   | Ok         | Ok      |                                  |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" CoSi2 Co 20 --format markdown 
| Region                           | Result     | Coating | Notes                              |
|----------------------------------|------------|---------|------------------------------------|
| [Co M₁-M₂ and 8 others; 1.0033>  | Interfered | Ok      | [Si L₁-L₂ and 5 others; 1.0000> on |
|                                  |            |         | [10,21)                            |
| [Co L₃-M₁ and 13 others; 0.9967> | Ok         | Ok      |                                    |
| [Co K-L₂ and 1 others; 0.8914>   | Ok         | Ok      |                                    |
| [Co K-M₂ and 2 others; 0.1086>   | Ok         | Ok      |                                    |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" CoCO3 Co 20 --format markdown 
| Region                           | Result     | Coating | Notes                            |
|----------------------------------|------------|---------|----------------------------------|
| [Co M₁-M₂ and 8 others; 1.0033>  | Interfered | Ok      | [C K-L₃ and 1 others; 1.0000> on |
|                                  |            |         | [15,38)                          |
| [Co L₃-M₁ and 13 others; 0.9967> | Interfered | Ok      | [O K-L₂ and 1 others; 1.0000> on |
|                                  |            |         | [40,64)                          |
| [Co K-L₂ and 1 others; 0.8914>   | Ok         | Ok      |                                  |
| [Co K-M₂ and 2 others; 0.1086>   | Ok         | Ok      |                                  |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" Ni Ni 20 --format markdown 
| Region                           | Result | Coating | Notes |
|----------------------------------|--------|---------|-------|
| [Ni M₁-M₂ and 8 others; 1.0025>  | Ok     | Ok      |       |
| [Ni L₃-M₁ and 13 others; 0.9975> | Ok     | Ok      |       |
| [Ni K-L₂ and 1 others; 0.8907>   | Ok     | Ok      |       |
| [Ni K-M₂ and 3 others; 0.1093>   | Ok     | Ok      |       |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" NiO Ni 20 --format markdown 
| Region                           | Result     | Coating | Notes                            |
|----------------------------------|------------|---------|----------------------------------|
| [Ni M₁-M₂ and 8 others; 1.0025>  | Ok         | Ok      |                                  |
| [Ni L₃-M₁ and 13 others; 0.9975> | Interfered | Ok      | [O K-L₂ and 1 others; 1.0000> on |
|                                  |            |         | [40,64)                          |
| [Ni K-L₂ and 1 others; 0.8907>   | Ok         | Ok      |                                  |
| [Ni K-M₂ and 3 others; 0.1093>   | Ok         | Ok      |                                  |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" NiAs Ni 20 --format markdown 
| Region                           | Result     | Coating | Notes                               |
|----------------------------------|------------|---------|-------------------------------------|
| [Ni M₁-M₂ and 8 others; 1.0025>  | Interfered | Ok      | [As M₄-N₂ and 12 others; 0.9999> on |
|                                  |            |         | [10,28)                             |
| [Ni L₃-M₁ and 13 others; 0.9975> | Interfered | Ok      | [As L₃-M₁ and 15 others; 0.9989> on |
|                                  |            |         | [99,160)                            |
| [Ni K-L₂ and 1 others; 0.8907>   | Ok         | Ok      |                                     |
| [Ni K-M₂ and 3 others; 0.1093>   | Ok         | Ok      |                                     |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" Ni2P Ni 20 --format markdown 
| Region                           | Result     | Coating | Notes                             |
|----------------------------------|------------|---------|-----------------------------------|
| [Ni M₁-M₂ and 8 others; 1.0025>  | Interfered | Ok      | [P L₁-L₂ and 6 others; 1.0000> on |
|                                  |            |         | [10,27)                           |
| [Ni L₃-M₁ and 13 others; 0.9975> | Ok         | Ok      |                                   |
| [Ni K-L₂ and 1 others; 0.8907>   | Ok         | Ok      |                                   |
| [Ni K-M₂ and 3 others; 0.1093>   | Ok         | Ok      |                                   |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" Ni2Si Ni 20 --format markdown 
| Region                           | Result     | Coating | Notes                              |
|----------------------------------|------------|---------|------------------------------------|
| [Ni M₁-M₂ and 8 others; 1.0025>  | Interfered | Ok      | [Si L₁-L₂ and 5 others; 1.0000> on |
|                                  |            |         | [10,21)                            |
| [Ni L₃-M₁ and 13 others; 0.9975> | Ok         | Ok      |                                    |
| [Ni K-L₂ and 1 others; 0.8907>   | Ok         | Ok      |                                    |
| [Ni K-M₂ and 3 others; 0.1093>   | Ok         | Ok      |                                    |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" NiSO4 Ni 20 --format markdown 
| Region                           | Result     | Coating | Notes                             |
|----------------------------------|------------|---------|-----------------------------------|
| [Ni M₁-M₂ and 8 others; 1.0025>  | Interfered | Ok      | [S L₁-L₂ and 7 others; 1.0000> on |
|                                  |            |         | [10,31)                           |
| [Ni L₃-M₁ and 13 others; 0.9975> | Interfered | Ok      | [O K-L₂ and 1 others; 1.0000> on  |
|                                  |            |         | [40,64)                           |
| [Ni K-L₂ and 1 others; 0.8907>   | Ok         | Ok      |                                   |
| [Ni K-M₂ and 3 others; 0.1093>   | Ok         | Ok      |                                   |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" Cu Cu 20 --format markdown 
| Region                           | Result | Coating | Notes |
|----------------------------------|--------|---------|-------|
| [Cu M₁-M₂ and 8 others; 1.0020>  | Ok     | Ok      |       |
| [Cu L₃-M₁ and 13 others; 0.9980> | Ok     | Ok      |       |
| [Cu K-L₂ and 1 others; 0.8916>   | Ok     | Ok      |       |
| [Cu K-M₂ and 3 others; 0.1084>   | Ok     | Ok      |       |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" CuO Cu 20 --format markdown 
| Region                           | Result | Coating | Notes |
|----------------------------------|--------|---------|-------|
| [Cu M₁-M₂ and 8 others; 1.0020>  | Ok     | Ok      |       |
| [Cu L₃-M₁ and 13 others; 0.9980> | Ok     | Ok      |       |
| [Cu K-L₂ and 1 others; 0.8916>   | Ok     | Ok      |       |
| [Cu K-M₂ and 3 others; 0.1084>   | Ok     | Ok      |       |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" CuS Cu 20 --format markdown 
| Region                           | Result     | Coating | Notes                             |
|----------------------------------|------------|---------|-----------------------------------|
| [Cu M₁-M₂ and 8 others; 1.0020>  | Interfered | Ok      | [S L₁-L₂ and 7 others; 1.0000> on |
|                                  |            |         | [10,31)                           |
| [Cu L₃-M₁ and 13 others; 0.9980> | Ok         | Ok      |                                   |
| [Cu K-L₂ and 1 others; 0.8916>   | Ok         | Ok      |                                   |
| [Cu K-M₂ and 3 others; 0.1084>   | Ok         | Ok      |                                   |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" CuI Cu 20 --format markdown 
| Region                           | Result     | Coating | Notes                              |
|----------------------------------|------------|---------|------------------------------------|
| [Cu M₁-M₂ and 8 others; 1.0020>  | Interfered | Ok      | [I N₄-O₂ and 16 others; 1.0369> on |
|                                  |            |         | [10,38)                            |
| [Cu L₃-M₁ and 13 others; 0.9980> | Interfered | Ok      | [I M₅-N₃ and 17 others; 0.9630> on |
|                                  |            |         | [37,113)                           |
| [Cu K-L₂ and 1 others; 0.8916>   | Ok         | Ok      |                                    |
| [Cu K-M₂ and 3 others; 0.1084>   | Ok         | Ok      |                                    |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" CuSO4 Cu 20 --format markdown 
| Region                           | Result     | Coating | Notes                             |
|----------------------------------|------------|---------|-----------------------------------|
| [Cu M₁-M₂ and 8 others; 1.0020>  | Interfered | Ok      | [S L₁-L₂ and 7 others; 1.0000> on |
|                                  |            |         | [10,31)                           |
| [Cu L₃-M₁ and 13 others; 0.9980> | Ok         | Ok      |                                   |
| [Cu K-L₂ and 1 others; 0.8916>   | Ok         | Ok      |                                   |
| [Cu K-M₂ and 3 others; 0.1084>   | Ok         | Ok      |                                   |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" Zn Zn 20 --format markdown 
| Region                           | Result | Coating | Notes |
|----------------------------------|--------|---------|-------|
| [Zn M₁-M₂ and 8 others; 1.0016>  | Ok     | Ok      |       |
| [Zn L₃-M₁ and 13 others; 0.9984> | Ok     | Ok      |       |
| [Zn K-L₂ and 1 others; 0.8896>   | Ok     | Ok      |       |
| [Zn K-M₂ and 3 others; 0.1104>   | Ok     | Ok      |       |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" ZnO Zn 20 --format markdown 
| Region                           | Result | Coating | Notes |
|----------------------------------|--------|---------|-------|
| [Zn M₁-M₂ and 8 others; 1.0016>  | Ok     | Ok      |       |
| [Zn L₃-M₁ and 13 others; 0.9984> | Ok     | Ok      |       |
| [Zn K-L₂ and 1 others; 0.8896>   | Ok     | Ok      |       |
| [Zn K-M₂ and 3 others; 0.1104>   | Ok     | Ok      |       |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" ZnSe Zn 20 --format markdown 
| Region                           | Result     | Coating | Notes                               |
|----------------------------------|------------|---------|-------------------------------------|
| [Zn M₁-M₂ and 8 others; 1.0016>  | Interfered | Ok      | [Se M₄-N₂ and 13 others; 1.0009> on |
|                                  |            |         | [10,31)                             |
| [Zn L₃-M₁ and 13 others; 0.9984> | Interfered | Ok      | [Se L₃-M₁ and 15 others; 0.9991> on |
|                                  |            |         | [108,174)                           |
| [Zn K-L₂ and 1 others; 0.8896>   | Ok         | Ok      |                                     |
| [Zn K-M₂ and 3 others; 0.1104>   | Ok         | Ok      |                                     |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" ZnS Zn 20 --format markdown 
| Region                           | Result     | Coating | Notes                             |
|----------------------------------|------------|---------|-----------------------------------|
| [Zn M₁-M₂ and 8 others; 1.0016>  | Interfered | Ok      | [S L₁-L₂ and 7 others; 1.0000> on |
|                                  |            |         | [10,31)                           |
| [Zn L₃-M₁ and 13 others; 0.9984> | Ok         | Ok      |                                   |
| [Zn K-L₂ and 1 others; 0.8896>   | Ok         | Ok      |                                   |
| [Zn K-M₂ and 3 others; 0.1104>   | Ok         | Ok      |                                   |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" ZnTe Zn 20 --format markdown 
| Region                           | Result     | Coating | Notes                               |
|----------------------------------|------------|---------|-------------------------------------|
| [Zn M₁-M₂ and 8 others; 1.0016>  | Interfered | Ok      | [Te N₅-O₃ and 33 others; 1.9977> on |
|                                  |            |         | [10,107)                            |
| [Zn L₃-M₁ and 13 others; 0.9984> | Interfered | Ok      | [Te N₅-O₃ and 33 others; 1.9977> on |
|                                  |            |         | [10,107)                            |
| [Zn K-L₂ and 1 others; 0.8896>   | Ok         | Ok      |                                     |
| [Zn K-M₂ and 3 others; 0.1104>   | Ok         | Ok      |                                     |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" Ga2O3 Ga 20 --format markdown 
| Region                           | Result | Coating | Notes |
|----------------------------------|--------|---------|-------|
| [Ga M₁-M₂ and 10 others; 1.0010> | Ok     | Ok      |       |
| [Ga L₃-M₁ and 15 others; 0.9987> | Ok     | Ok      |       |
| [Ga K-L₂ and 1 others; 0.8868>   | Ok     | Ok      |       |
| [Ga K-M₂ and 5 others; 0.1132>   | Ok     | Ok      |       |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" GaSb Ga 20 --format markdown 
| Region                           | Result     | Coating | Notes                               |
|----------------------------------|------------|---------|-------------------------------------|
| [Ga M₁-M₂ and 10 others; 1.0010> | Interfered | Ok      | [Sb N₁-N₂ and 32 others; 1.9973> on |
|                                  |            |         | [10,100)                            |
| [Ga L₃-M₁ and 15 others; 0.9987> | Interfered | Ok      | [Sb N₁-N₂ and 32 others; 1.9973> on |
|                                  |            |         | [10,100)                            |
| [Ga K-L₂ and 1 others; 0.8868>   | Ok         | Ok      |                                     |
| [Ga K-M₂ and 5 others; 0.1132>   | Ok         | Ok      |                                     |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" GaAs Ga 20 --format markdown 
| Region                           | Result     | Coating | Notes                               |
|----------------------------------|------------|---------|-------------------------------------|
| [Ga M₁-M₂ and 10 others; 1.0010> | Interfered | Ok      | [As M₄-N₂ and 12 others; 0.9999> on |
|                                  |            |         | [10,28)                             |
| [Ga L₃-M₁ and 15 others; 0.9987> | Interfered | Ok      | [As L₃-M₁ and 15 others; 0.9989> on |
|                                  |            |         | [99,160)                            |
| [Ga K-L₂ and 1 others; 0.8868>   | Ok         | Ok      |                                     |
| [Ga K-M₂ and 5 others; 0.1132>   | Interfered | Ok      | [As K-L₂ and 1 others; 0.8794> on   |
|                                  |            |         | [1019,1086)                         |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" GaN Ga 20 --format markdown 
| Region                           | Result | Coating | Notes |
|----------------------------------|--------|---------|-------|
| [Ga M₁-M₂ and 10 others; 1.0010> | Ok     | Ok      |       |
| [Ga L₃-M₁ and 15 others; 0.9987> | Ok     | Ok      |       |
| [Ga K-L₂ and 1 others; 0.8868>   | Ok     | Ok      |       |
| [Ga K-M₂ and 5 others; 0.1132>   | Ok     | Ok      |       |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" GaP Ga 20 --format markdown 
| Region                           | Result     | Coating | Notes                             |
|----------------------------------|------------|---------|-----------------------------------|
| [Ga M₁-M₂ and 10 others; 1.0010> | Interfered | Ok      | [P L₁-L₂ and 6 others; 1.0000> on |
|                                  |            |         | [10,27)                           |
| [Ga L₃-M₁ and 15 others; 0.9987> | Ok         | Ok      |                                   |
| [Ga K-L₂ and 1 others; 0.8868>   | Ok         | Ok      |                                   |
| [Ga K-M₂ and 5 others; 0.1132>   | Ok         | Ok      |                                   |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" Ga2Se3 Ga 20 --format markdown 
| Region                           | Result     | Coating | Notes                               |
|----------------------------------|------------|---------|-------------------------------------|
| [Ga M₁-M₂ and 10 others; 1.0010> | Interfered | Ok      | [Se M₄-N₂ and 13 others; 1.0009> on |
|                                  |            |         | [10,31)                             |
| [Ga L₃-M₁ and 15 others; 0.9987> | Interfered | Ok      | [Se L₃-M₁ and 15 others; 0.9991> on |
|                                  |            |         | [108,174)                           |
| [Ga K-L₂ and 1 others; 0.8868>   | Ok         | Ok      |                                     |
| [Ga K-M₂ and 5 others; 0.1132>   | Ok         | Ok      |                                     |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" GaS Ga 20 --format markdown 
| Region                           | Result     | Coating | Notes                             |
|----------------------------------|------------|---------|-----------------------------------|
| [Ga M₁-M₂ and 10 others; 1.0010> | Interfered | Ok      | [S L₁-L₂ and 7 others; 1.0000> on |
|                                  |            |         | [10,31)                           |
| [Ga L₃-M₁ and 15 others; 0.9987> | Ok         | Ok      |                                   |
| [Ga K-L₂ and 1 others; 0.8868>   | Ok         | Ok      |                                   |
| [Ga K-M₂ and 5 others; 0.1132>   | Ok         | Ok      |                                   |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" Ge Ge 20 --format markdown 
| Region                           | Result | Coating | Notes |
|----------------------------------|--------|---------|-------|
| [Ge M₁-M₂ and 10 others; 0.9966> | Ok     | Ok      |       |
| [Ge L₃-M₁ and 15 others; 0.9989> | Ok     | Ok      |       |
| [Ge K-L₂ and 1 others; 0.8833>   | Ok     | Ok      |       |
| [Ge K-M₂ and 5 others; 0.1167>   | Ok     | Ok      |       |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" GeO2 Ge 20 --format markdown 
| Region                           | Result | Coating | Notes |
|----------------------------------|--------|---------|-------|
| [Ge M₁-M₂ and 10 others; 0.9966> | Ok     | Ok      |       |
| [Ge L₃-M₁ and 15 others; 0.9989> | Ok     | Ok      |       |
| [Ge K-L₂ and 1 others; 0.8833>   | Ok     | Ok      |       |
| [Ge K-M₂ and 5 others; 0.1167>   | Ok     | Ok      |       |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" As As 20 --format markdown 
| Region                           | Result | Coating | Notes |
|----------------------------------|--------|---------|-------|
| [As M₄-N₂ and 12 others; 0.9999> | Ok     | Ok      |       |
| [As L₃-M₁ and 15 others; 0.9989> | Ok     | Ok      |       |
| [As K-L₂ and 1 others; 0.8794>   | Ok     | Ok      |       |
| [As K-M₂ and 5 others; 0.1206>   | Ok     | Ok      |       |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" AsO3 As 20 --format markdown 
| Region                           | Result | Coating | Notes |
|----------------------------------|--------|---------|-------|
| [As M₄-N₂ and 12 others; 0.9999> | Ok     | Ok      |       |
| [As L₃-M₁ and 15 others; 0.9989> | Ok     | Ok      |       |
| [As K-L₂ and 1 others; 0.8794>   | Ok     | Ok      |       |
| [As K-M₂ and 5 others; 0.1206>   | Ok     | Ok      |       |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" InAs As 20 --format markdown 
| Region                           | Result     | Coating | Notes                               |
|----------------------------------|------------|---------|-------------------------------------|
| [As M₄-N₂ and 12 others; 0.9999> | Interfered | Ok      | [In N₁-N₂ and 32 others; 2.0008> on |
|                                  |            |         | [10,85)                             |
| [As L₃-M₁ and 15 others; 0.9989> | Ok         | Ok      |                                     |
| [As K-L₂ and 1 others; 0.8794>   | Ok         | Ok      |                                     |
| [As K-M₂ and 5 others; 0.1206>   | Ok         | Ok      |                                     |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" As As 20 --format markdown 
| Region                           | Result | Coating | Notes |
|----------------------------------|--------|---------|-------|
| [As M₄-N₂ and 12 others; 0.9999> | Ok     | Ok      |       |
| [As L₃-M₁ and 15 others; 0.9989> | Ok     | Ok      |       |
| [As K-L₂ and 1 others; 0.8794>   | Ok     | Ok      |       |
| [As K-M₂ and 5 others; 0.1206>   | Ok     | Ok      |       |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" As2Te3 As 20 --format markdown 
| Region                           | Result     | Coating | Notes                               |
|----------------------------------|------------|---------|-------------------------------------|
| [As M₄-N₂ and 12 others; 0.9999> | Interfered | Ok      | [Te N₅-O₃ and 33 others; 1.9977> on |
|                                  |            |         | [10,107)                            |
| [As L₃-M₁ and 15 others; 0.9989> | Interfered | Ok      | [Te N₅-O₃ and 33 others; 1.9977> on |
|                                  |            |         | [10,107)                            |
| [As K-L₂ and 1 others; 0.8794>   | Ok         | Ok      |                                     |
| [As K-M₂ and 5 others; 0.1206>   | Ok         | Ok      |                                     |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" As2Se3 As 20 --format markdown 
| Region                           | Result     | Coating | Notes                               |
|----------------------------------|------------|---------|-------------------------------------|
| [As M₄-N₂ and 12 others; 0.9999> | Interfered | Ok      | [Se M₄-N₂ and 13 others; 1.0009> on |
|                                  |            |         | [10,31)                             |
| [As L₃-M₁ and 15 others; 0.9989> | Interfered | Ok      | [Se L₃-M₁ and 15 others; 0.9991> on |
|                                  |            |         | [108,174)                           |
| [As K-L₂ and 1 others; 0.8794>   | Ok         | Ok      |                                     |
| [As K-M₂ and 5 others; 0.1206>   | Interfered | Ok      | [Se K-L₂ and 1 others; 0.8753> on   |
|                                  |            |         | [1086,1155)                         |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" GaAs As 20 --format markdown 
| Region                           | Result     | Coating | Notes                               |
|----------------------------------|------------|---------|-------------------------------------|
| [As M₄-N₂ and 12 others; 0.9999> | Interfered | Ok      | [Ga M₁-M₂ and 10 others; 1.0010> on |
|                                  |            |         | [10,24)                             |
| [As L₃-M₁ and 15 others; 0.9989> | Interfered | Ok      | [Ga L₃-M₁ and 15 others; 0.9987> on |
|                                  |            |         | [84,134)                            |
| [As K-L₂ and 1 others; 0.8794>   | Interfered | Ok      | [Ga K-M₂ and 5 others; 0.1132> on   |
|                                  |            |         | [998,1054)                          |
| [As K-M₂ and 5 others; 0.1206>   | Ok         | Ok      |                                     |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" NiAs As 20 --format markdown 
| Region                           | Result     | Coating | Notes                               |
|----------------------------------|------------|---------|-------------------------------------|
| [As M₄-N₂ and 12 others; 0.9999> | Interfered | Ok      | [Ni M₁-M₂ and 8 others; 1.0025> on  |
|                                  |            |         | [10,22)                             |
| [As L₃-M₁ and 15 others; 0.9989> | Interfered | Ok      | [Ni L₃-M₁ and 13 others; 0.9975> on |
|                                  |            |         | [62,105)                            |
| [As K-L₂ and 1 others; 0.8794>   | Ok         | Ok      |                                     |
| [As K-M₂ and 5 others; 0.1206>   | Ok         | Ok      |                                     |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" Se Se 20 --format markdown 
| Region                           | Result | Coating | Notes |
|----------------------------------|--------|---------|-------|
| [Se M₄-N₂ and 13 others; 1.0009> | Ok     | Ok      |       |
| [Se L₃-M₁ and 15 others; 0.9991> | Ok     | Ok      |       |
| [Se K-L₂ and 1 others; 0.8753>   | Ok     | Ok      |       |
| [Se K-M₂ and 5 others; 0.1247>   | Ok     | Ok      |       |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" CdSe Se 20 --format markdown 
| Region                           | Result     | Coating | Notes                               |
|----------------------------------|------------|---------|-------------------------------------|
| [Se M₄-N₂ and 13 others; 1.0009> | Interfered | Ok      | [Cd N₁-N₂ and 25 others; 2.0006> on |
|                                  |            |         | [10,80)                             |
| [Se L₃-M₁ and 15 others; 0.9991> | Ok         | Ok      |                                     |
| [Se K-L₂ and 1 others; 0.8753>   | Ok         | Ok      |                                     |
| [Se K-M₂ and 5 others; 0.1247>   | Ok         | Ok      |                                     |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" Ga2Se3 Se 20 --format markdown 
| Region                           | Result     | Coating | Notes                               |
|----------------------------------|------------|---------|-------------------------------------|
| [Se M₄-N₂ and 13 others; 1.0009> | Interfered | Ok      | [Ga M₁-M₂ and 10 others; 1.0010> on |
|                                  |            |         | [10,24)                             |
| [Se L₃-M₁ and 15 others; 0.9991> | Interfered | Ok      | [Ga L₃-M₁ and 15 others; 0.9987> on |
|                                  |            |         | [84,134)                            |
| [Se K-L₂ and 1 others; 0.8753>   | Ok         | Ok      |                                     |
| [Se K-M₂ and 5 others; 0.1247>   | Ok         | Ok      |                                     |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" In2Se3 Se 20 --format markdown 
| Region                           | Result     | Coating | Notes                               |
|----------------------------------|------------|---------|-------------------------------------|
| [Se M₄-N₂ and 13 others; 1.0009> | Interfered | Ok      | [In N₁-N₂ and 32 others; 2.0008> on |
|                                  |            |         | [10,85)                             |
| [Se L₃-M₁ and 15 others; 0.9991> | Ok         | Ok      |                                     |
| [Se K-L₂ and 1 others; 0.8753>   | Ok         | Ok      |                                     |
| [Se K-M₂ and 5 others; 0.1247>   | Ok         | Ok      |                                     |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" PbSe Se 20 --format markdown 
| Region                           | Result     | Coating | Notes                               |
|----------------------------------|------------|---------|-------------------------------------|
| [Se M₄-N₂ and 13 others; 1.0009> | Interfered | Ok      | [Pb O₁-O₂ and 39 others; 2.0042> on |
|                                  |            |         | [10,105)                            |
| [Se L₃-M₁ and 15 others; 0.9991> | Interfered | Ok      | [Pb M₄-N₂ and 25 others; 0.9964> on |
|                                  |            |         | [168,365)                           |
| [Se K-L₂ and 1 others; 0.8753>   | Interfered | Ok      | [Pb L₂-M₁; 0.0051> on [1111,1158)   |
| [Se K-M₂ and 5 others; 0.1247>   | Interfered | Ok      | [Pb L₂-M₃ and 16 others; 0.3852> on |
|                                  |            |         | [1188,1358)                         |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" As2Se3 Se 20 --format markdown 
| Region                           | Result     | Coating | Notes                               |
|----------------------------------|------------|---------|-------------------------------------|
| [Se M₄-N₂ and 13 others; 1.0009> | Interfered | Ok      | [As M₄-N₂ and 12 others; 0.9999> on |
|                                  |            |         | [10,28)                             |
| [Se L₃-M₁ and 15 others; 0.9991> | Interfered | Ok      | [As L₃-M₁ and 15 others; 0.9989> on |
|                                  |            |         | [99,160)                            |
| [Se K-L₂ and 1 others; 0.8753>   | Interfered | Ok      | [As K-M₂ and 5 others; 0.1206> on   |
|                                  |            |         | [1142,1208)                         |
| [Se K-M₂ and 5 others; 0.1247>   | Ok         | Ok      |                                     |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" ZnSe Se 20 --format markdown 
| Region                           | Result     | Coating | Notes                               |
|----------------------------------|------------|---------|-------------------------------------|
| [Se M₄-N₂ and 13 others; 1.0009> | Interfered | Ok      | [Zn M₁-M₂ and 8 others; 1.0016> on  |
|                                  |            |         | [10,24)                             |
| [Se L₃-M₁ and 15 others; 0.9991> | Interfered | Ok      | [Zn L₃-M₁ and 13 others; 0.9984> on |
|                                  |            |         | [76,122)                            |
| [Se K-L₂ and 1 others; 0.8753>   | Ok         | Ok      |                                     |
| [Se K-M₂ and 5 others; 0.1247>   | Ok         | Ok      |                                     |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" KBr Br 20 --format markdown 
| Region                           | Result     | Coating | Notes                              |
|----------------------------------|------------|---------|------------------------------------|
| [Br M₅-N₃ and 13 others; 1.0008> | Interfered | Ok      | [K L₁-L₂ and 10 others; 1.0000> on |
|                                  |            |         | [10,46)                            |
| [Br L₃-M₁ and 15 others; 0.9991> | Ok         | Ok      |                                    |
| [Br K-L₂ and 1 others; 0.8708>   | Ok         | Ok      |                                    |
| [Br K-M₂ and 5 others; 0.1292>   | Ok         | Ok      |                                    |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" CsBr Br 20 --format markdown 
| Region                           | Result     | Coating | Notes                               |
|----------------------------------|------------|---------|-------------------------------------|
| [Br M₅-N₃ and 13 others; 1.0008> | Interfered | Ok      | [Cs N₁-N₂ and 17 others; 1.0277> on |
|                                  |            |         | [10,41)                             |
| [Br L₃-M₁ and 15 others; 0.9991> | Interfered | Ok      | [Cs M₅-N₃ and 17 others; 0.9731> on |
|                                  |            |         | [44,128)                            |
| [Br K-L₂ and 1 others; 0.8708>   | Ok         | Ok      |                                     |
| [Br K-M₂ and 5 others; 0.1292>   | Ok         | Ok      |                                     |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" RbBr Br 20 --format markdown 
| Region                           | Result     | Coating | Notes                               |
|----------------------------------|------------|---------|-------------------------------------|
| [Br M₅-N₃ and 13 others; 1.0008> | Interfered | Ok      | [Rb N₁-N₂ and 15 others; 2.0007> on |
|                                  |            |         | [10,40)                             |
| [Br L₃-M₁ and 15 others; 0.9991> | Interfered | Ok      | [Rb L₃-M₁ and 15 others; 0.9993> on |
|                                  |            |         | [135,215)                           |
| [Br K-L₂ and 1 others; 0.8708>   | Ok         | Ok      |                                     |
| [Br K-M₂ and 5 others; 0.1292>   | Interfered | Ok      | [Rb K-L₂ and 1 others; 0.8616> on   |
|                                  |            |         | [1299,1375)                         |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" TlBr Br 20 --format markdown 
| Region                           | Result     | Coating | Notes                                  |
|----------------------------------|------------|---------|----------------------------------------|
| [Br M₅-N₃ and 13 others; 1.0008> | Interfered | Ok      | [Tl O₁-O₂ and 39 others; 2.0043> on    |
|                                  |            |         | [10,102)                               |
| [Br L₃-M₁ and 15 others; 0.9991> | Interfered | Ok      | [Tl M₄-N₂ and 23 others; 0.9962> on    |
|                                  |            |         | [163,352)                              |
| [Br K-L₂ and 1 others; 0.8708>   | Interfered | Ok      | [Tl L₂-M₃ and 16 others; 0.3853> on    |
|                                  |            |         | [1156,1316)                            |
| [Br K-M₂ and 5 others; 0.1292>   | Interfered | Ok      | [Tl L₂-M₃ and 16 others; 0.3853> on    |
|                                  |            |         | [1156,1316), [Tl L₂-N₁ and 12 others;  |
|                                  |            |         | 0.0868> on [1361,1549)                 |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>rem spex suitable "EDAX All" Kr Kr 20 --format markdown 

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>rem spex suitable "EDAX All" Rb Rb 20 --format markdown 

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" RbBr Rb 20 --format markdown 
| Region                           | Result     | Coating | Notes                               |
|----------------------------------|------------|---------|-------------------------------------|
| [Rb N₁-N₂ and 15 others; 2.0007> | Interfered | Ok      | [Br M₅-N₃ and 13 others; 1.0008> on |
|                                  |            |         | [10,33)                             |
| [Rb L₃-M₁ and 15 others; 0.9993> | Interfered | Ok      | [Br L₃-M₁ and 15 others; 0.9991> on |
|                                  |            |         | [116,186)                           |
| [Rb K-L₂ and 1 others; 0.8616>   | Interfered | Ok      | [Br K-M₂ and 5 others; 0.1292> on   |
|                                  |            |         | [1297,1372)                         |
| [Rb K-M₂ and 5 others; 0.1384>   | Ok         | Ok      |                                     |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" RbI Rb 20 --format markdown 
| Region                           | Result     | Coating | Notes                              |
|----------------------------------|------------|---------|------------------------------------|
| [Rb N₁-N₂ and 15 others; 2.0007> | Interfered | Ok      | [I N₄-O₂ and 16 others; 1.0369> on |
|                                  |            |         | [10,38), [I M₅-N₃ and 17 others;   |
|                                  |            |         | 0.9630> on [37,113)                |
| [Rb L₃-M₁ and 15 others; 0.9993> | Ok         | Ok      |                                    |
| [Rb K-L₂ and 1 others; 0.8616>   | Ok         | Ok      |                                    |
| [Rb K-M₂ and 5 others; 0.1384>   | Ok         | Ok      |                                    |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" Rb2SO4 Rb 20 --format markdown 
| Region                           | Result     | Coating | Notes                             |
|----------------------------------|------------|---------|-----------------------------------|
| [Rb N₁-N₂ and 15 others; 2.0007> | Interfered | Ok      | [S L₁-L₂ and 7 others; 1.0000> on |
|                                  |            |         | [10,31)                           |
| [Rb L₃-M₁ and 15 others; 0.9993> | Interfered | Ok      | [S K-L₂ and 3 others; 1.0000> on  |
|                                  |            |         | [213,261)                         |
| [Rb K-L₂ and 1 others; 0.8616>   | Ok         | Ok      |                                   |
| [Rb K-M₂ and 5 others; 0.1384>   | Ok         | Ok      |                                   |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>rem spex suitable "EDAX All" Sr Sr 20 --format markdown 

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" Sr(NO3)2 Sr 20 --format markdown 
| Region                           | Result     | Coating | Notes                                  |
|----------------------------------|------------|---------|----------------------------------------|
| [Sr N₁-N₂ and 15 others; 2.0007> | Interfered | Ok      | [N K-L₂ and 1 others; 1.0000> on       |
|                                  |            |         | [27,51), [O K-L₂ and 1 others; 1.0000> |
|                                  |            |         | on [40,64)                             |
| [Sr L₃-M₁ and 15 others; 0.9993> | Ok         | Ok      |                                        |
| [Sr K-L₂ and 1 others; 0.8571>   | Ok         | Ok      |                                        |
| [Sr K-M₂ and 5 others; 0.1429>   | Ok         | Ok      |                                        |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" SrTiO2 Sr 20 --format markdown 
| Region                           | Result     | Coating | Notes                                  |
|----------------------------------|------------|---------|----------------------------------------|
| [Sr N₁-N₂ and 15 others; 2.0007> | Interfered | Ok      | [O K-L₂ and 1 others; 1.0000> on       |
|                                  |            |         | [40,64), [Ti M₁-M₂ and 5 others;       |
|                                  |            |         | 1.0269> on [10,19), [Ti L₃-M₁ and 13   |
|                                  |            |         | others; 0.9693> on [29,63)             |
| [Sr L₃-M₁ and 15 others; 0.9993> | Ok         | Ok      |                                        |
| [Sr K-L₂ and 1 others; 0.8571>   | Ok         | Ok      |                                        |
| [Sr K-M₂ and 5 others; 0.1429>   | Ok         | Ok      |                                        |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" SrF2 Sr 20 --format markdown 
| Region                           | Result | Coating | Notes |
|----------------------------------|--------|---------|-------|
| [Sr N₁-N₂ and 15 others; 2.0007> | Ok     | Ok      |       |
| [Sr L₃-M₁ and 15 others; 0.9993> | Ok     | Ok      |       |
| [Sr K-L₂ and 1 others; 0.8571>   | Ok     | Ok      |       |
| [Sr K-M₂ and 5 others; 0.1429>   | Ok     | Ok      |       |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" Y Y 20 --format markdown 
| Region                          | Result | Coating | Notes |
|---------------------------------|--------|---------|-------|
| [Y N₁-N₂ and 19 others; 1.9416> | Ok     | Ok      |       |
| [Y L₃-M₁ and 18 others; 0.9993> | Ok     | Ok      |       |
| [Y K-L₂ and 1 others; 0.8528>   | Ok     | Ok      |       |
| [Y K-M₂ and 5 others; 0.1472>   | Ok     | Ok      |       |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" Y2O3 Y 20 --format markdown 
| Region                          | Result     | Coating | Notes                            |
|---------------------------------|------------|---------|----------------------------------|
| [Y N₁-N₂ and 19 others; 1.9416> | Interfered | Ok      | [O K-L₂ and 1 others; 1.0000> on |
|                                 |            |         | [40,64)                          |
| [Y L₃-M₁ and 18 others; 0.9993> | Ok         | Ok      |                                  |
| [Y K-L₂ and 1 others; 0.8528>   | Ok         | Ok      |                                  |
| [Y K-M₂ and 5 others; 0.1472>   | Ok         | Ok      |                                  |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" Zr Zr 20 --format markdown 
| Region                           | Result | Coating | Notes |
|----------------------------------|--------|---------|-------|
| [Zr N₃-N₅ and 20 others; 1.9648> | Ok     | Ok      |       |
| [Zr L₃-M₁ and 18 others; 0.9994> | Ok     | Ok      |       |
| [Zr K-L₂ and 1 others; 0.8489>   | Ok     | Ok      |       |
| [Zr K-M₂ and 5 others; 0.1511>   | Ok     | Ok      |       |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" ZrB2 Zr 20 --format markdown 
| Region                           | Result     | Coating | Notes                       |
|----------------------------------|------------|---------|-----------------------------|
| [Zr N₃-N₅ and 20 others; 1.9648> | Interfered | Ok      | [B K-L₂; 1.0000> on [10,29) |
| [Zr L₃-M₁ and 18 others; 0.9994> | Ok         | Ok      |                             |
| [Zr K-L₂ and 1 others; 0.8489>   | Ok         | Ok      |                             |
| [Zr K-M₂ and 5 others; 0.1511>   | Ok         | Ok      |                             |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" ZrC Zr 20 --format markdown 
| Region                           | Result     | Coating | Notes                            |
|----------------------------------|------------|---------|----------------------------------|
| [Zr N₃-N₅ and 20 others; 1.9648> | Interfered | Ok      | [C K-L₃ and 1 others; 1.0000> on |
|                                  |            |         | [15,38)                          |
| [Zr L₃-M₁ and 18 others; 0.9994> | Ok         | Ok      |                                  |
| [Zr K-L₂ and 1 others; 0.8489>   | Ok         | Ok      |                                  |
| [Zr K-M₂ and 5 others; 0.1511>   | Ok         | Ok      |                                  |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" ZrN Zr 20 --format markdown 
| Region                           | Result     | Coating | Notes                            |
|----------------------------------|------------|---------|----------------------------------|
| [Zr N₃-N₅ and 20 others; 1.9648> | Interfered | Ok      | [N K-L₂ and 1 others; 1.0000> on |
|                                  |            |         | [27,51)                          |
| [Zr L₃-M₁ and 18 others; 0.9994> | Ok         | Ok      |                                  |
| [Zr K-L₂ and 1 others; 0.8489>   | Ok         | Ok      |                                  |
| [Zr K-M₂ and 5 others; 0.1511>   | Ok         | Ok      |                                  |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" ZrO2 Zr 20 --format markdown 
| Region                           | Result     | Coating | Notes                            |
|----------------------------------|------------|---------|----------------------------------|
| [Zr N₃-N₅ and 20 others; 1.9648> | Interfered | Ok      | [O K-L₂ and 1 others; 1.0000> on |
|                                  |            |         | [40,64)                          |
| [Zr L₃-M₁ and 18 others; 0.9994> | Ok         | Ok      |                                  |
| [Zr K-L₂ and 1 others; 0.8489>   | Ok         | Ok      |                                  |
| [Zr K-M₂ and 5 others; 0.1511>   | Ok         | Ok      |                                  |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" Nb Nb 20 --format markdown 
| Region                           | Result | Coating | Notes |
|----------------------------------|--------|---------|-------|
| [Nb N₁-N₂ and 22 others; 1.9916> | Ok     | Ok      |       |
| [Nb L₃-M₁ and 18 others; 0.9994> | Ok     | Ok      |       |
| [Nb K-L₂ and 1 others; 0.8455>   | Ok     | Ok      |       |
| [Nb K-M₂ and 5 others; 0.1545>   | Ok     | Ok      |       |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" Li2Nb2O6 Nb 20 --format markdown 
| Region                           | Result     | Coating | Notes                                  |
|----------------------------------|------------|---------|----------------------------------------|
| [Nb N₁-N₂ and 22 others; 1.9916> | Interfered | Ok      | [Li K-L₁; 1.0000> on [10,15), [O K-L₂  |
|                                  |            |         | and 1 others; 1.0000> on [40,64)       |
| [Nb L₃-M₁ and 18 others; 0.9994> | Ok         | Ok      |                                        |
| [Nb K-L₂ and 1 others; 0.8455>   | Ok         | Ok      |                                        |
| [Nb K-M₂ and 5 others; 0.1545>   | Ok         | Ok      |                                        |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" Nb2O5 Nb 20 --format markdown 
| Region                           | Result     | Coating | Notes                            |
|----------------------------------|------------|---------|----------------------------------|
| [Nb N₁-N₂ and 22 others; 1.9916> | Interfered | Ok      | [O K-L₂ and 1 others; 1.0000> on |
|                                  |            |         | [40,64)                          |
| [Nb L₃-M₁ and 18 others; 0.9994> | Ok         | Ok      |                                  |
| [Nb K-L₂ and 1 others; 0.8455>   | Ok         | Ok      |                                  |
| [Nb K-M₂ and 5 others; 0.1545>   | Ok         | Ok      |                                  |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" Nb2O3 Nb 20 --format markdown 
| Region                           | Result     | Coating | Notes                            |
|----------------------------------|------------|---------|----------------------------------|
| [Nb N₁-N₂ and 22 others; 1.9916> | Interfered | Ok      | [O K-L₂ and 1 others; 1.0000> on |
|                                  |            |         | [40,64)                          |
| [Nb L₃-M₁ and 18 others; 0.9994> | Ok         | Ok      |                                  |
| [Nb K-L₂ and 1 others; 0.8455>   | Ok         | Ok      |                                  |
| [Nb K-M₂ and 5 others; 0.1545>   | Ok         | Ok      |                                  |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" NbSi2 Nb 20 --format markdown 
| Region                           | Result     | Coating | Notes                              |
|----------------------------------|------------|---------|------------------------------------|
| [Nb N₁-N₂ and 22 others; 1.9916> | Interfered | Ok      | [Si L₁-L₂ and 5 others; 1.0000> on |
|                                  |            |         | [10,21)                            |
| [Nb L₃-M₁ and 18 others; 0.9994> | Interfered | Ok      | [Si K-L₂ and 3 others; 1.0000> on  |
|                                  |            |         | [157,195)                          |
| [Nb K-L₂ and 1 others; 0.8455>   | Ok         | Ok      |                                    |
| [Nb K-M₂ and 5 others; 0.1545>   | Ok         | Ok      |                                    |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" Mo Mo 20 --format markdown 
| Region                           | Result | Coating | Notes |
|----------------------------------|--------|---------|-------|
| [Mo N₁-N₂ and 22 others; 1.9920> | Ok     | Ok      |       |
| [Mo L₃-M₁ and 16 others; 0.9952> | Ok     | Ok      |       |
| [Mo L₁-N₂ and 1 others; 0.0042>  | Ok     | Ok      |       |
| [Mo K-L₂ and 1 others; 0.8425>   | Ok     | Ok      |       |
| [Mo K-M₂ and 5 others; 0.1575>   | Ok     | Ok      |       |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" CaMoO4 Mo 20 --format markdown 
| Region                           | Result     | Coating | Notes                             |
|----------------------------------|------------|---------|-----------------------------------|
| [Mo N₁-N₂ and 22 others; 1.9920> | Interfered | Ok      | [O K-L₂ and 1 others; 1.0000> on  |
|                                  |            |         | [40,64), [Ca L₁-L₂ and 10 others; |
|                                  |            |         | 1.0000> on [10,52)                |
| [Mo L₃-M₁ and 16 others; 0.9952> | Ok         | Ok      |                                   |
| [Mo L₁-N₂ and 1 others; 0.0042>  | Ok         | Ok      |                                   |
| [Mo K-L₂ and 1 others; 0.8425>   | Ok         | Ok      |                                   |
| [Mo K-M₂ and 5 others; 0.1575>   | Ok         | Ok      |                                   |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" MoS2 Mo 20 --format markdown 
| Region                           | Result     | Coating | Notes                             |
|----------------------------------|------------|---------|-----------------------------------|
| [Mo N₁-N₂ and 22 others; 1.9920> | Interfered | Ok      | [S L₁-L₂ and 7 others; 1.0000> on |
|                                  |            |         | [10,31)                           |
| [Mo L₃-M₁ and 16 others; 0.9952> | Interfered | Ok      | [S K-L₂ and 3 others; 1.0000> on  |
|                                  |            |         | [213,261)                         |
| [Mo L₁-N₂ and 1 others; 0.0042>  | Ok         | Ok      |                                   |
| [Mo K-L₂ and 1 others; 0.8425>   | Ok         | Ok      |                                   |
| [Mo K-M₂ and 5 others; 0.1575>   | Ok         | Ok      |                                   |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" MoO3 Mo 20 --format markdown 
| Region                           | Result     | Coating | Notes                            |
|----------------------------------|------------|---------|----------------------------------|
| [Mo N₁-N₂ and 22 others; 1.9920> | Interfered | Ok      | [O K-L₂ and 1 others; 1.0000> on |
|                                  |            |         | [40,64)                          |
| [Mo L₃-M₁ and 16 others; 0.9952> | Ok         | Ok      |                                  |
| [Mo L₁-N₂ and 1 others; 0.0042>  | Ok         | Ok      |                                  |
| [Mo K-L₂ and 1 others; 0.8425>   | Ok         | Ok      |                                  |
| [Mo K-M₂ and 5 others; 0.1575>   | Ok         | Ok      |                                  |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" Mo2C Mo 20 --format markdown 
| Region                           | Result     | Coating | Notes                            |
|----------------------------------|------------|---------|----------------------------------|
| [Mo N₁-N₂ and 22 others; 1.9920> | Interfered | Ok      | [C K-L₃ and 1 others; 1.0000> on |
|                                  |            |         | [15,38)                          |
| [Mo L₃-M₁ and 16 others; 0.9952> | Ok         | Ok      |                                  |
| [Mo L₁-N₂ and 1 others; 0.0042>  | Ok         | Ok      |                                  |
| [Mo K-L₂ and 1 others; 0.8425>   | Ok         | Ok      |                                  |
| [Mo K-M₂ and 5 others; 0.1575>   | Ok         | Ok      |                                  |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>rem spex suitable "EDAX All" Tc Tc 20 --format markdown 

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" Ru Ru 20 --format markdown 
| Region                           | Result | Coating | Notes |
|----------------------------------|--------|---------|-------|
| [Ru N₁-N₂ and 23 others; 2.0005> | Ok     | Ok      |       |
| [Ru L₃-M₁ and 18 others; 0.9995> | Ok     | Ok      |       |
| [Ru K-L₂ and 1 others; 0.8375>   | Ok     | Ok      |       |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" Rh Rh 20 --format markdown 
| Region                           | Result | Coating | Notes |
|----------------------------------|--------|---------|-------|
| [Rh N₁-N₂ and 15 others; 1.7486> | Ok     | Ok      |       |
| [Rh L₁-L₃ and 7 others; 0.2519>  | Ok     | Ok      |       |
| [Rh L₃-M₁ and 18 others; 0.9994> | Ok     | Ok      |       |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" Pd Pd 20 --format markdown 
| Region                           | Result | Coating | Notes |
|----------------------------------|--------|---------|-------|
| [Pd N₁-N₂ and 21 others; 2.0005> | Ok     | Ok      |       |
| [Pd L₃-M₁ and 18 others; 0.9994> | Ok     | Ok      |       |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" Ag Ag 20 --format markdown 
| Region                           | Result | Coating | Notes |
|----------------------------------|--------|---------|-------|
| [Ag N₁-N₂ and 25 others; 2.0005> | Ok     | Ok      |       |
| [Ag L₃-M₁ and 18 others; 0.9918> | Ok     | Ok      |       |
| [Ag L₁-N₂ and 1 others; 0.0075>  | Ok     | Ok      |       |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" AgCl Ag 20 --format markdown 
| Region                           | Result     | Coating | Notes                              |
|----------------------------------|------------|---------|------------------------------------|
| [Ag N₁-N₂ and 25 others; 2.0005> | Interfered | Ok      | [Cl L₁-L₂ and 8 others; 1.0000> on |
|                                  |            |         | [10,36)                            |
| [Ag L₃-M₁ and 18 others; 0.9918> | Interfered | Ok      | [Cl K-L₂ and 3 others; 1.0000> on  |
|                                  |            |         | [243,297)                          |
| [Ag L₁-N₂ and 1 others; 0.0075>  | Ok         | Ok      |                                    |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" Ag2S Ag 20 --format markdown 
| Region                           | Result     | Coating | Notes                             |
|----------------------------------|------------|---------|-----------------------------------|
| [Ag N₁-N₂ and 25 others; 2.0005> | Interfered | Ok      | [S L₁-L₂ and 7 others; 1.0000> on |
|                                  |            |         | [10,31)                           |
| [Ag L₃-M₁ and 18 others; 0.9918> | Interfered | Ok      | [S K-L₂ and 3 others; 1.0000> on  |
|                                  |            |         | [213,261)                         |
| [Ag L₁-N₂ and 1 others; 0.0075>  | Ok         | Ok      |                                   |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" Ag2Te Ag 20 --format markdown 
| Region                           | Result     | Coating | Notes                               |
|----------------------------------|------------|---------|-------------------------------------|
| [Ag N₁-N₂ and 25 others; 2.0005> | Interfered | Ok      | [Te N₅-O₃ and 33 others; 1.9977> on |
|                                  |            |         | [10,107)                            |
| [Ag L₃-M₁ and 18 others; 0.9918> | Interfered | Ok      | [Te L₃-M₁ and 24 others; 0.9991> on |
|                                  |            |         | [317,506)                           |
| [Ag L₁-N₂ and 1 others; 0.0075>  | Interfered | Ok      | [Te L₃-M₁ and 24 others; 0.9991> on |
|                                  |            |         | [317,506)                           |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" Cd Cd 20 --format markdown 
| Region                           | Result | Coating | Notes |
|----------------------------------|--------|---------|-------|
| [Cd N₁-N₂ and 25 others; 2.0006> | Ok     | Ok      |       |
| [Cd L₃-M₁ and 21 others; 0.9994> | Ok     | Ok      |       |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" CdO Cd 20 --format markdown 
| Region                           | Result     | Coating | Notes                            |
|----------------------------------|------------|---------|----------------------------------|
| [Cd N₁-N₂ and 25 others; 2.0006> | Interfered | Ok      | [O K-L₂ and 1 others; 1.0000> on |
|                                  |            |         | [40,64)                          |
| [Cd L₃-M₁ and 21 others; 0.9994> | Ok         | Ok      |                                  |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" CdSe Cd 20 --format markdown 
| Region                           | Result     | Coating | Notes                               |
|----------------------------------|------------|---------|-------------------------------------|
| [Cd N₁-N₂ and 25 others; 2.0006> | Interfered | Ok      | [Se M₄-N₂ and 13 others; 1.0009> on |
|                                  |            |         | [10,31)                             |
| [Cd L₃-M₁ and 21 others; 0.9994> | Ok         | Ok      |                                     |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" CdS Cd 20 --format markdown 
| Region                           | Result     | Coating | Notes                             |
|----------------------------------|------------|---------|-----------------------------------|
| [Cd N₁-N₂ and 25 others; 2.0006> | Interfered | Ok      | [S L₁-L₂ and 7 others; 1.0000> on |
|                                  |            |         | [10,31)                           |
| [Cd L₃-M₁ and 21 others; 0.9994> | Ok         | Ok      |                                   |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" CdTe Cd 20 --format markdown 
| Region                           | Result     | Coating | Notes                               |
|----------------------------------|------------|---------|-------------------------------------|
| [Cd N₁-N₂ and 25 others; 2.0006> | Interfered | Ok      | [Te N₅-O₃ and 33 others; 1.9977> on |
|                                  |            |         | [10,107)                            |
| [Cd L₃-M₁ and 21 others; 0.9994> | Interfered | Ok      | [Te L₃-M₁ and 24 others; 0.9991> on |
|                                  |            |         | [317,506)                           |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" In In 20 --format markdown 
| Region                           | Result | Coating | Notes |
|----------------------------------|--------|---------|-------|
| [In N₁-N₂ and 32 others; 2.0008> | Ok     | Ok      |       |
| [In L₃-M₁ and 24 others; 0.9992> | Ok     | Ok      |       |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" In2O3 In 20 --format markdown 
| Region                           | Result     | Coating | Notes                            |
|----------------------------------|------------|---------|----------------------------------|
| [In N₁-N₂ and 32 others; 2.0008> | Interfered | Ok      | [O K-L₂ and 1 others; 1.0000> on |
|                                  |            |         | [40,64)                          |
| [In L₃-M₁ and 24 others; 0.9992> | Ok         | Ok      |                                  |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" InSb In 20 --format markdown 
| Region                           | Result     | Coating | Notes                               |
|----------------------------------|------------|---------|-------------------------------------|
| [In N₁-N₂ and 32 others; 2.0008> | Interfered | Ok      | [Sb N₁-N₂ and 32 others; 1.9973> on |
|                                  |            |         | [10,100)                            |
| [In L₃-M₁ and 24 others; 0.9992> | Interfered | Ok      | [Sb L₃-M₁ and 24 others; 0.9992> on |
|                                  |            |         | [303,480)                           |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" InAs In 20 --format markdown 
| Region                           | Result     | Coating | Notes                               |
|----------------------------------|------------|---------|-------------------------------------|
| [In N₁-N₂ and 32 others; 2.0008> | Interfered | Ok      | [As M₄-N₂ and 12 others; 0.9999> on |
|                                  |            |         | [10,28)                             |
| [In L₃-M₁ and 24 others; 0.9992> | Ok         | Ok      |                                     |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" InP In 20 --format markdown 
| Region                           | Result     | Coating | Notes                             |
|----------------------------------|------------|---------|-----------------------------------|
| [In N₁-N₂ and 32 others; 2.0008> | Interfered | Ok      | [P L₁-L₂ and 6 others; 1.0000> on |
|                                  |            |         | [10,27)                           |
| [In L₃-M₁ and 24 others; 0.9992> | Ok         | Ok      |                                   |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" In2Se3 In 20 --format markdown 
| Region                           | Result     | Coating | Notes                               |
|----------------------------------|------------|---------|-------------------------------------|
| [In N₁-N₂ and 32 others; 2.0008> | Interfered | Ok      | [Se M₄-N₂ and 13 others; 1.0009> on |
|                                  |            |         | [10,31)                             |
| [In L₃-M₁ and 24 others; 0.9992> | Ok         | Ok      |                                     |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" InS In 20 --format markdown 
| Region                           | Result     | Coating | Notes                             |
|----------------------------------|------------|---------|-----------------------------------|
| [In N₁-N₂ and 32 others; 2.0008> | Interfered | Ok      | [S L₁-L₂ and 7 others; 1.0000> on |
|                                  |            |         | [10,31)                           |
| [In L₃-M₁ and 24 others; 0.9992> | Ok         | Ok      |                                   |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" In2Te3 In 20 --format markdown 
| Region                           | Result     | Coating | Notes                               |
|----------------------------------|------------|---------|-------------------------------------|
| [In N₁-N₂ and 32 others; 2.0008> | Interfered | Ok      | [Te N₅-O₃ and 33 others; 1.9977> on |
|                                  |            |         | [10,107)                            |
| [In L₃-M₁ and 24 others; 0.9992> | Interfered | Ok      | [Te L₃-M₁ and 24 others; 0.9991> on |
|                                  |            |         | [317,506)                           |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" Sn Sn 20 --format markdown 
| Region                           | Result | Coating | Notes |
|----------------------------------|--------|---------|-------|
| [Sn N₁-N₂ and 32 others; 1.9997> | Ok     | Ok      |       |
| [Sn L₃-M₁ and 24 others; 0.9992> | Ok     | Ok      |       |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" SnO2 Sn 20 --format markdown 
| Region                           | Result     | Coating | Notes                            |
|----------------------------------|------------|---------|----------------------------------|
| [Sn N₁-N₂ and 32 others; 1.9997> | Interfered | Ok      | [O K-L₂ and 1 others; 1.0000> on |
|                                  |            |         | [40,64)                          |
| [Sn L₃-M₁ and 24 others; 0.9992> | Ok         | Ok      |                                  |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" Sb Sb 20 --format markdown 
| Region                           | Result | Coating | Notes |
|----------------------------------|--------|---------|-------|
| [Sb N₁-N₂ and 32 others; 1.9973> | Ok     | Ok      |       |
| [Sb L₃-M₁ and 24 others; 0.9992> | Ok     | Ok      |       |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" Sb2S3 Sb 20 --format markdown 
| Region                           | Result     | Coating | Notes                             |
|----------------------------------|------------|---------|-----------------------------------|
| [Sb N₁-N₂ and 32 others; 1.9973> | Interfered | Ok      | [S L₁-L₂ and 7 others; 1.0000> on |
|                                  |            |         | [10,31)                           |
| [Sb L₃-M₁ and 24 others; 0.9992> | Ok         | Ok      |                                   |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" GaSb Sb 20 --format markdown 
| Region                           | Result     | Coating | Notes                               |
|----------------------------------|------------|---------|-------------------------------------|
| [Sb N₁-N₂ and 32 others; 1.9973> | Interfered | Ok      | [Ga M₁-M₂ and 10 others; 1.0010> on |
|                                  |            |         | [10,24), [Ga L₃-M₁ and 15 others;   |
|                                  |            |         | 0.9987> on [84,134)                 |
| [Sb L₃-M₁ and 24 others; 0.9992> | Ok         | Ok      |                                     |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" InSb Sb 20 --format markdown 
| Region                           | Result     | Coating | Notes                               |
|----------------------------------|------------|---------|-------------------------------------|
| [Sb N₁-N₂ and 32 others; 1.9973> | Interfered | Ok      | [In N₁-N₂ and 32 others; 2.0008> on |
|                                  |            |         | [10,85)                             |
| [Sb L₃-M₁ and 24 others; 0.9992> | Interfered | Ok      | [In L₃-M₁ and 24 others; 0.9992> on |
|                                  |            |         | [275,432)                           |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" Te Te 20 --format markdown 
| Region                           | Result | Coating | Notes |
|----------------------------------|--------|---------|-------|
| [Te N₅-O₃ and 33 others; 1.9977> | Ok     | Ok      |       |
| [Te L₃-M₁ and 24 others; 0.9991> | Ok     | Ok      |       |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" CdTe Te 20 --format markdown 
| Region                           | Result     | Coating | Notes                               |
|----------------------------------|------------|---------|-------------------------------------|
| [Te N₅-O₃ and 33 others; 1.9977> | Interfered | Ok      | [Cd N₁-N₂ and 25 others; 2.0006> on |
|                                  |            |         | [10,80)                             |
| [Te L₃-M₁ and 24 others; 0.9991> | Interfered | Ok      | [Cd L₃-M₁ and 21 others; 0.9994> on |
|                                  |            |         | [261,410)                           |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" In2Te3 Te 20 --format markdown 
| Region                           | Result     | Coating | Notes                               |
|----------------------------------|------------|---------|-------------------------------------|
| [Te N₅-O₃ and 33 others; 1.9977> | Interfered | Ok      | [In N₁-N₂ and 32 others; 2.0008> on |
|                                  |            |         | [10,85)                             |
| [Te L₃-M₁ and 24 others; 0.9991> | Interfered | Ok      | [In L₃-M₁ and 24 others; 0.9992> on |
|                                  |            |         | [275,432)                           |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" PbTe Te 20 --format markdown 
| Region                           | Result     | Coating | Notes                               |
|----------------------------------|------------|---------|-------------------------------------|
| [Te N₅-O₃ and 33 others; 1.9977> | Interfered | Ok      | [Pb O₁-O₂ and 39 others; 2.0042> on |
|                                  |            |         | [10,105)                            |
| [Te L₃-M₁ and 24 others; 0.9991> | Interfered | Ok      | [Pb M₄-N₂ and 25 others; 0.9964> on |
|                                  |            |         | [168,365), [Pb M₁-O₂ and 1 others;  |
|                                  |            |         | 0.0008> on [363,387)                |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" HgTe Te 20 --format markdown 
| Region                           | Result     | Coating | Notes                               |
|----------------------------------|------------|---------|-------------------------------------|
| [Te N₅-O₃ and 33 others; 1.9977> | Interfered | Ok      | [Hg O₁-O₂ and 33 others; 2.0044> on |
|                                  |            |         | [10,98)                             |
| [Te L₃-M₁ and 24 others; 0.9991> | Interfered | Ok      | [Hg M₄-N₂ and 25 others; 0.9969> on |
|                                  |            |         | [157,360)                           |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" Ag2Te Te 20 --format markdown 
| Region                           | Result     | Coating | Notes                               |
|----------------------------------|------------|---------|-------------------------------------|
| [Te N₅-O₃ and 33 others; 1.9977> | Interfered | Ok      | [Ag N₁-N₂ and 25 others; 2.0005> on |
|                                  |            |         | [10,75)                             |
| [Te L₃-M₁ and 24 others; 0.9991> | Interfered | Ok      | [Ag L₃-M₁ and 18 others; 0.9918> on |
|                                  |            |         | [248,369), [Ag L₁-N₂ and 1 others;  |
|                                  |            |         | 0.0075> on [360,389)                |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" TeO2 Te 20 --format markdown 
| Region                           | Result     | Coating | Notes                            |
|----------------------------------|------------|---------|----------------------------------|
| [Te N₅-O₃ and 33 others; 1.9977> | Interfered | Ok      | [O K-L₂ and 1 others; 1.0000> on |
|                                  |            |         | [40,64)                          |
| [Te L₃-M₁ and 24 others; 0.9991> | Ok         | Ok      |                                  |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" ZnTe Te 20 --format markdown 
| Region                           | Result     | Coating | Notes                              |
|----------------------------------|------------|---------|------------------------------------|
| [Te N₅-O₃ and 33 others; 1.9977> | Interfered | Ok      | [Zn M₁-M₂ and 8 others; 1.0016> on |
|                                  |            |         | [10,24), [Zn L₃-M₁ and 13 others;  |
|                                  |            |         | 0.9984> on [76,122)                |
| [Te L₃-M₁ and 24 others; 0.9991> | Ok         | Ok      |                                    |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" CsI I 20 --format markdown 
| Region                          | Result     | Coating | Notes                               |
|---------------------------------|------------|---------|-------------------------------------|
| [I N₄-O₂ and 16 others; 1.0369> | Interfered | Ok      | [Cs N₁-N₂ and 17 others; 1.0277> on |
|                                 |            |         | [10,41)                             |
| [I M₅-N₃ and 17 others; 0.9630> | Interfered | Ok      | [Cs N₁-N₂ and 17 others; 1.0277> on |
|                                 |            |         | [10,41), [Cs M₅-N₃ and 17 others;   |
|                                 |            |         | 0.9731> on [44,128)                 |
| [I L₃-M₁ and 24 others; 0.9991> | Interfered | Ok      | [Cs L₃-M₁ and 25 others; 0.9991> on |
|                                 |            |         | [362,585)                           |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" CuI I 20 --format markdown 
| Region                          | Result     | Coating | Notes                               |
|---------------------------------|------------|---------|-------------------------------------|
| [I N₄-O₂ and 16 others; 1.0369> | Interfered | Ok      | [Cu M₁-M₂ and 8 others; 1.0020> on  |
|                                 |            |         | [10,23)                             |
| [I M₅-N₃ and 17 others; 0.9630> | Interfered | Ok      | [Cu L₃-M₁ and 13 others; 0.9980> on |
|                                 |            |         | [69,113)                            |
| [I L₃-M₁ and 24 others; 0.9991> | Ok         | Ok      |                                     |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" RbI I 20 --format markdown 
| Region                          | Result     | Coating | Notes                               |
|---------------------------------|------------|---------|-------------------------------------|
| [I N₄-O₂ and 16 others; 1.0369> | Interfered | Ok      | [Rb N₁-N₂ and 15 others; 2.0007> on |
|                                 |            |         | [10,40)                             |
| [I M₅-N₃ and 17 others; 0.9630> | Interfered | Ok      | [Rb N₁-N₂ and 15 others; 2.0007> on |
|                                 |            |         | [10,40)                             |
| [I L₃-M₁ and 24 others; 0.9991> | Ok         | Ok      |                                     |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" TlI I 20 --format markdown 
| Region                          | Result     | Coating | Notes                               |
|---------------------------------|------------|---------|-------------------------------------|
| [I N₄-O₂ and 16 others; 1.0369> | Interfered | Ok      | [Tl O₁-O₂ and 39 others; 2.0043> on |
|                                 |            |         | [10,102)                            |
| [I M₅-N₃ and 17 others; 0.9630> | Interfered | Ok      | [Tl O₁-O₂ and 39 others; 2.0043> on |
|                                 |            |         | [10,102)                            |
| [I L₃-M₁ and 24 others; 0.9991> | Interfered | Ok      | [Tl M₄-N₂ and 23 others; 0.9962> on |
|                                 |            |         | [163,352), [Tl M₁-O₂ and 1 others;  |
|                                 |            |         | 0.0008> on [349,373)                |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>rem spex suitable "EDAX All" Xe Xe 20 --format markdown 

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" CsBr Cs 20 --format markdown 
| Region                           | Result     | Coating | Notes                               |
|----------------------------------|------------|---------|-------------------------------------|
| [Cs N₁-N₂ and 17 others; 1.0277> | Interfered | Ok      | [Br M₅-N₃ and 13 others; 1.0008> on |
|                                  |            |         | [10,33)                             |
| [Cs M₅-N₃ and 17 others; 0.9731> | Interfered | Ok      | [Br L₃-M₁ and 15 others; 0.9991> on |
|                                  |            |         | [116,186)                           |
| [Cs L₃-M₁ and 25 others; 0.9991> | Ok         | Ok      |                                     |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" CsI Cs 20 --format markdown 
| Region                           | Result     | Coating | Notes                              |
|----------------------------------|------------|---------|------------------------------------|
| [Cs N₁-N₂ and 17 others; 1.0277> | Interfered | Ok      | [I N₄-O₂ and 16 others; 1.0369> on |
|                                  |            |         | [10,38), [I M₅-N₃ and 17 others;   |
|                                  |            |         | 0.9630> on [37,113)                |
| [Cs M₅-N₃ and 17 others; 0.9731> | Interfered | Ok      | [I M₅-N₃ and 17 others; 0.9630> on |
|                                  |            |         | [37,113)                           |
| [Cs L₃-M₁ and 25 others; 0.9991> | Interfered | Ok      | [I L₃-M₁ and 24 others; 0.9991> on |
|                                  |            |         | [332,531)                          |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" CsNO3 Cs 20 --format markdown 
| Region                           | Result     | Coating | Notes                                  |
|----------------------------------|------------|---------|----------------------------------------|
| [Cs N₁-N₂ and 17 others; 1.0277> | Interfered | Ok      | [N K-L₂ and 1 others; 1.0000> on       |
|                                  |            |         | [27,51), [O K-L₂ and 1 others; 1.0000> |
|                                  |            |         | on [40,64)                             |
| [Cs M₅-N₃ and 17 others; 0.9731> | Interfered | Ok      | [N K-L₂ and 1 others; 1.0000> on       |
|                                  |            |         | [27,51), [O K-L₂ and 1 others; 1.0000> |
|                                  |            |         | on [40,64)                             |
| [Cs L₃-M₁ and 25 others; 0.9991> | Ok         | Ok      |                                        |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" BaF2 Ba 20 --format markdown 
| Region                           | Result     | Coating | Notes                            |
|----------------------------------|------------|---------|----------------------------------|
| [Ba N₁-N₂ and 17 others; 1.0237> | Ok         | Ok      |                                  |
| [Ba M₅-N₃ and 17 others; 0.9771> | Interfered | Ok      | [F K-L₂ and 1 others; 1.0000> on |
|                                  |            |         | [54,80)                          |
| [Ba L₃-M₁ and 27 others; 0.9992> | Ok         | Ok      |                                  |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" Ba(NO3)2 Ba 20 --format markdown 
| Region                           | Result     | Coating | Notes                                  |
|----------------------------------|------------|---------|----------------------------------------|
| [Ba N₁-N₂ and 17 others; 1.0237> | Interfered | Ok      | [N K-L₂ and 1 others; 1.0000> on       |
|                                  |            |         | [27,51), [O K-L₂ and 1 others; 1.0000> |
|                                  |            |         | on [40,64)                             |
| [Ba M₅-N₃ and 17 others; 0.9771> | Interfered | Ok      | [N K-L₂ and 1 others; 1.0000> on       |
|                                  |            |         | [27,51), [O K-L₂ and 1 others; 1.0000> |
|                                  |            |         | on [40,64)                             |
| [Ba L₃-M₁ and 27 others; 0.9992> | Ok         | Ok      |                                        |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" BaTiO2 Ba 20 --format markdown 
| Region                           | Result     | Coating | Notes                                  |
|----------------------------------|------------|---------|----------------------------------------|
| [Ba N₁-N₂ and 17 others; 1.0237> | Interfered | Ok      | [O K-L₂ and 1 others; 1.0000> on       |
|                                  |            |         | [40,64), [Ti M₁-M₂ and 5 others;       |
|                                  |            |         | 1.0269> on [10,19), [Ti L₃-M₁ and 13   |
|                                  |            |         | others; 0.9693> on [29,63)             |
| [Ba M₅-N₃ and 17 others; 0.9771> | Interfered | Ok      | [O K-L₂ and 1 others; 1.0000> on       |
|                                  |            |         | [40,64), [Ti L₃-M₁ and 13 others;      |
|                                  |            |         | 0.9693> on [29,63)                     |
| [Ba L₃-M₁ and 27 others; 0.9992> | Interfered | Ok      | [Ti K-L₂ and 3 others; 1.0000> on      |
|                                  |            |         | [428,513)                              |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" BaAl2Si2O8 Ba 20 --format markdown 
| Region                           | Result     | Coating | Notes                               |
|----------------------------------|------------|---------|-------------------------------------|
| [Ba N₁-N₂ and 17 others; 1.0237> | Interfered | Ok      | [O K-L₂ and 1 others; 1.0000> on    |
|                                  |            |         | [40,64), [Al L₁-L₂ and 5 others;    |
|                                  |            |         | 1.0000> on [10,17), [Si L₁-L₂ and 5 |
|                                  |            |         | others; 1.0000> on [10,21)          |
| [Ba M₅-N₃ and 17 others; 0.9771> | Interfered | Ok      | [O K-L₂ and 1 others; 1.0000> on    |
|                                  |            |         | [40,64), [Al K-L₂ and 3 others;     |
|                                  |            |         | 1.0000> on [133,166)                |
| [Ba L₃-M₁ and 27 others; 0.9992> | Ok         | Ok      |                                     |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" BaSi2O5 Ba 20 --format markdown 
| Region                           | Result     | Coating | Notes                            |
|----------------------------------|------------|---------|----------------------------------|
| [Ba N₁-N₂ and 17 others; 1.0237> | Interfered | Ok      | [O K-L₂ and 1 others; 1.0000> on |
|                                  |            |         | [40,64), [Si L₁-L₂ and 5 others; |
|                                  |            |         | 1.0000> on [10,21)               |
| [Ba M₅-N₃ and 17 others; 0.9771> | Interfered | Ok      | [O K-L₂ and 1 others; 1.0000> on |
|                                  |            |         | [40,64)                          |
| [Ba L₃-M₁ and 27 others; 0.9992> | Ok         | Ok      |                                  |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" BaCl Ba 20 --format markdown 
| Region                           | Result     | Coating | Notes                              |
|----------------------------------|------------|---------|------------------------------------|
| [Ba N₁-N₂ and 17 others; 1.0237> | Interfered | Ok      | [Cl L₁-L₂ and 8 others; 1.0000> on |
|                                  |            |         | [10,36)                            |
| [Ba M₅-N₃ and 17 others; 0.9771> | Ok         | Ok      |                                    |
| [Ba L₃-M₁ and 27 others; 0.9992> | Ok         | Ok      |                                    |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" LaB6 La 20 --format markdown 
| Region                           | Result     | Coating | Notes                       |
|----------------------------------|------------|---------|-----------------------------|
| [La N₁-N₂ and 17 others; 1.0205> | Interfered | Ok      | [B K-L₂; 1.0000> on [10,29) |
| [La M₅-N₃ and 15 others; 0.9790> | Ok         | Ok      |                             |
| [La M₁-O₂ and 1 others; 0.0014>  | Ok         | Ok      |                             |
| [La L₃-M₁ and 27 others; 0.9992> | Ok         | Ok      |                             |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" La2O3 La 20 --format markdown 
| Region                           | Result     | Coating | Notes                            |
|----------------------------------|------------|---------|----------------------------------|
| [La N₁-N₂ and 17 others; 1.0205> | Interfered | Ok      | [O K-L₂ and 1 others; 1.0000> on |
|                                  |            |         | [40,64)                          |
| [La M₅-N₃ and 15 others; 0.9790> | Interfered | Ok      | [O K-L₂ and 1 others; 1.0000> on |
|                                  |            |         | [40,64)                          |
| [La M₁-O₂ and 1 others; 0.0014>  | Ok         | Ok      |                                  |
| [La L₃-M₁ and 27 others; 0.9992> | Ok         | Ok      |                                  |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" LaF3 La 20 --format markdown 
| Region                           | Result     | Coating | Notes                            |
|----------------------------------|------------|---------|----------------------------------|
| [La N₁-N₂ and 17 others; 1.0205> | Ok         | Ok      |                                  |
| [La M₅-N₃ and 15 others; 0.9790> | Interfered | Ok      | [F K-L₂ and 1 others; 1.0000> on |
|                                  |            |         | [54,80)                          |
| [La M₁-O₂ and 1 others; 0.0014>  | Ok         | Ok      |                                  |
| [La L₃-M₁ and 27 others; 0.9992> | Ok         | Ok      |                                  |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" CeF3 Ce 20 --format markdown 
| Region                           | Result     | Coating | Notes                            |
|----------------------------------|------------|---------|----------------------------------|
| [Ce N₁-N₂ and 18 others; 1.0160> | Ok         | Ok      |                                  |
| [Ce M₅-N₃ and 18 others; 0.9812> | Interfered | Ok      | [F K-L₂ and 1 others; 1.0000> on |
|                                  |            |         | [54,80)                          |
| [Ce M₁-O₂ and 1 others; 0.0013>  | Ok         | Ok      |                                  |
| [Ce L₃-M₁ and 27 others; 0.9991> | Ok         | Ok      |                                  |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" CeO2 Ce 20 --format markdown 
| Region                           | Result     | Coating | Notes                            |
|----------------------------------|------------|---------|----------------------------------|
| [Ce N₁-N₂ and 18 others; 1.0160> | Interfered | Ok      | [O K-L₂ and 1 others; 1.0000> on |
|                                  |            |         | [40,64)                          |
| [Ce M₅-N₃ and 18 others; 0.9812> | Interfered | Ok      | [O K-L₂ and 1 others; 1.0000> on |
|                                  |            |         | [40,64)                          |
| [Ce M₁-O₂ and 1 others; 0.0013>  | Ok         | Ok      |                                  |
| [Ce L₃-M₁ and 27 others; 0.9991> | Ok         | Ok      |                                  |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" CeP5O14 Ce 20 --format markdown 
| Region                           | Result     | Coating | Notes                            |
|----------------------------------|------------|---------|----------------------------------|
| [Ce N₁-N₂ and 18 others; 1.0160> | Interfered | Ok      | [O K-L₂ and 1 others; 1.0000> on |
|                                  |            |         | [40,64), [P L₁-L₂ and 6 others;  |
|                                  |            |         | 1.0000> on [10,27)               |
| [Ce M₅-N₃ and 18 others; 0.9812> | Interfered | Ok      | [O K-L₂ and 1 others; 1.0000> on |
|                                  |            |         | [40,64)                          |
| [Ce M₁-O₂ and 1 others; 0.0013>  | Ok         | Ok      |                                  |
| [Ce L₃-M₁ and 27 others; 0.9991> | Ok         | Ok      |                                  |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" CeAl2 Ce 20 --format markdown 
| Region                           | Result     | Coating | Notes                              |
|----------------------------------|------------|---------|------------------------------------|
| [Ce N₁-N₂ and 18 others; 1.0160> | Interfered | Ok      | [Al L₁-L₂ and 5 others; 1.0000> on |
|                                  |            |         | [10,17)                            |
| [Ce M₅-N₃ and 18 others; 0.9812> | Ok         | Ok      |                                    |
| [Ce M₁-O₂ and 1 others; 0.0013>  | Interfered | Ok      | [Al K-L₂ and 3 others; 1.0000> on  |
|                                  |            |         | [133,166)                          |
| [Ce L₃-M₁ and 27 others; 0.9991> | Ok         | Ok      |                                    |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>rem spex suitable "EDAX All" Pr Pr 20 --format markdown 

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" PrF3 Pr 20 --format markdown 
| Region                           | Result     | Coating | Notes                            |
|----------------------------------|------------|---------|----------------------------------|
| [Pr O₁-O₃ and 20 others; 2.0163> | Ok         | Ok      |                                  |
| [Pr M₅-N₃ and 18 others; 0.9833> | Interfered | Ok      | [F K-L₂ and 1 others; 1.0000> on |
|                                  |            |         | [54,80)                          |
| [Pr M₁-O₂ and 1 others; 0.0013>  | Ok         | Ok      |                                  |
| [Pr L₃-M₁ and 27 others; 0.9991> | Ok         | Ok      |                                  |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" PrSi2 Pr 20 --format markdown 
| Region                           | Result     | Coating | Notes                              |
|----------------------------------|------------|---------|------------------------------------|
| [Pr O₁-O₃ and 20 others; 2.0163> | Interfered | Ok      | [Si L₁-L₂ and 5 others; 1.0000> on |
|                                  |            |         | [10,21)                            |
| [Pr M₅-N₃ and 18 others; 0.9833> | Ok         | Ok      |                                    |
| [Pr M₁-O₂ and 1 others; 0.0013>  | Ok         | Ok      |                                    |
| [Pr L₃-M₁ and 27 others; 0.9991> | Ok         | Ok      |                                    |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" PrP5O14 Pr 20 --format markdown 
| Region                           | Result     | Coating | Notes                            |
|----------------------------------|------------|---------|----------------------------------|
| [Pr O₁-O₃ and 20 others; 2.0163> | Interfered | Ok      | [O K-L₂ and 1 others; 1.0000> on |
|                                  |            |         | [40,64), [P L₁-L₂ and 6 others;  |
|                                  |            |         | 1.0000> on [10,27)               |
| [Pr M₅-N₃ and 18 others; 0.9833> | Interfered | Ok      | [O K-L₂ and 1 others; 1.0000> on |
|                                  |            |         | [40,64)                          |
| [Pr M₁-O₂ and 1 others; 0.0013>  | Ok         | Ok      |                                  |
| [Pr L₃-M₁ and 27 others; 0.9991> | Ok         | Ok      |                                  |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" Nd Nd 20 --format markdown 
| Region                           | Result | Coating | Notes |
|----------------------------------|--------|---------|-------|
| [Nd O₁-O₂ and 21 others; 2.0146> | Ok     | Ok      |       |
| [Nd M₅-N₃ and 18 others; 0.9850> | Ok     | Ok      |       |
| [Nd M₁-O₂ and 1 others; 0.0013>  | Ok     | Ok      |       |
| [Nd L₃-M₁ and 27 others; 0.9990> | Ok     | Ok      |       |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" NdSi2 Nd 20 --format markdown 
| Region                           | Result     | Coating | Notes                              |
|----------------------------------|------------|---------|------------------------------------|
| [Nd O₁-O₂ and 21 others; 2.0146> | Interfered | Ok      | [Si L₁-L₂ and 5 others; 1.0000> on |
|                                  |            |         | [10,21)                            |
| [Nd M₅-N₃ and 18 others; 0.9850> | Ok         | Ok      |                                    |
| [Nd M₁-O₂ and 1 others; 0.0013>  | Interfered | Ok      | [Si K-L₂ and 3 others; 1.0000> on  |
|                                  |            |         | [157,195)                          |
| [Nd L₃-M₁ and 27 others; 0.9990> | Ok         | Ok      |                                    |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" NdF3 Nd 20 --format markdown 
| Region                           | Result     | Coating | Notes                            |
|----------------------------------|------------|---------|----------------------------------|
| [Nd O₁-O₂ and 21 others; 2.0146> | Ok         | Ok      |                                  |
| [Nd M₅-N₃ and 18 others; 0.9850> | Interfered | Ok      | [F K-L₂ and 1 others; 1.0000> on |
|                                  |            |         | [54,80)                          |
| [Nd M₁-O₂ and 1 others; 0.0013>  | Ok         | Ok      |                                  |
| [Nd L₃-M₁ and 27 others; 0.9990> | Ok         | Ok      |                                  |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" Nd2O3 Nd 20 --format markdown 
| Region                           | Result     | Coating | Notes                            |
|----------------------------------|------------|---------|----------------------------------|
| [Nd O₁-O₂ and 21 others; 2.0146> | Interfered | Ok      | [O K-L₂ and 1 others; 1.0000> on |
|                                  |            |         | [40,64)                          |
| [Nd M₅-N₃ and 18 others; 0.9850> | Interfered | Ok      | [O K-L₂ and 1 others; 1.0000> on |
|                                  |            |         | [40,64)                          |
| [Nd M₁-O₂ and 1 others; 0.0013>  | Ok         | Ok      |                                  |
| [Nd L₃-M₁ and 27 others; 0.9990> | Ok         | Ok      |                                  |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" NdP5O14 Nd 20 --format markdown 
| Region                           | Result     | Coating | Notes                            |
|----------------------------------|------------|---------|----------------------------------|
| [Nd O₁-O₂ and 21 others; 2.0146> | Interfered | Ok      | [O K-L₂ and 1 others; 1.0000> on |
|                                  |            |         | [40,64), [P L₁-L₂ and 6 others;  |
|                                  |            |         | 1.0000> on [10,27)               |
| [Nd M₅-N₃ and 18 others; 0.9850> | Interfered | Ok      | [O K-L₂ and 1 others; 1.0000> on |
|                                  |            |         | [40,64)                          |
| [Nd M₁-O₂ and 1 others; 0.0013>  | Ok         | Ok      |                                  |
| [Nd L₃-M₁ and 27 others; 0.9990> | Ok         | Ok      |                                  |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>rem spex suitable "EDAX All" Pm Pm 20 --format markdown 

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" Sm Sm 20 --format markdown 
| Region                           | Result | Coating | Notes |
|----------------------------------|--------|---------|-------|
| [Sm O₁-O₂ and 21 others; 2.0119> | Ok     | Ok      |       |
| [Sm M₅-N₃ and 18 others; 0.9879> | Ok     | Ok      |       |
| [Sm M₁-O₂ and 1 others; 0.0012>  | Ok     | Ok      |       |
| [Sm L₃-M₁ and 2 others; 0.0184>  | Ok     | Ok      |       |
| [Sm L₂-M₁ and 15 others; 0.9061> | Ok     | Ok      |       |
| [Sm L₂-N₁ and 9 others; 0.0745>  | Ok     | Ok      |       |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" SmF3 Sm 20 --format markdown 
| Region                           | Result     | Coating | Notes                            |
|----------------------------------|------------|---------|----------------------------------|
| [Sm O₁-O₂ and 21 others; 2.0119> | Ok         | Ok      |                                  |
| [Sm M₅-N₃ and 18 others; 0.9879> | Interfered | Ok      | [F K-L₂ and 1 others; 1.0000> on |
|                                  |            |         | [54,80)                          |
| [Sm M₁-O₂ and 1 others; 0.0012>  | Ok         | Ok      |                                  |
| [Sm L₃-M₁ and 2 others; 0.0184>  | Ok         | Ok      |                                  |
| [Sm L₂-M₁ and 15 others; 0.9061> | Ok         | Ok      |                                  |
| [Sm L₂-N₁ and 9 others; 0.0745>  | Ok         | Ok      |                                  |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" Sm2O3 Sm 20 --format markdown 
| Region                           | Result     | Coating | Notes                            |
|----------------------------------|------------|---------|----------------------------------|
| [Sm O₁-O₂ and 21 others; 2.0119> | Interfered | Ok      | [O K-L₂ and 1 others; 1.0000> on |
|                                  |            |         | [40,64)                          |
| [Sm M₅-N₃ and 18 others; 0.9879> | Ok         | Ok      |                                  |
| [Sm M₁-O₂ and 1 others; 0.0012>  | Ok         | Ok      |                                  |
| [Sm L₃-M₁ and 2 others; 0.0184>  | Ok         | Ok      |                                  |
| [Sm L₂-M₁ and 15 others; 0.9061> | Ok         | Ok      |                                  |
| [Sm L₂-N₁ and 9 others; 0.0745>  | Ok         | Ok      |                                  |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" SmP5O14 Sm 20 --format markdown 
| Region                           | Result     | Coating | Notes                            |
|----------------------------------|------------|---------|----------------------------------|
| [Sm O₁-O₂ and 21 others; 2.0119> | Interfered | Ok      | [O K-L₂ and 1 others; 1.0000> on |
|                                  |            |         | [40,64), [P L₁-L₂ and 6 others;  |
|                                  |            |         | 1.0000> on [10,27)               |
| [Sm M₅-N₃ and 18 others; 0.9879> | Ok         | Ok      |                                  |
| [Sm M₁-O₂ and 1 others; 0.0012>  | Ok         | Ok      |                                  |
| [Sm L₃-M₁ and 2 others; 0.0184>  | Ok         | Ok      |                                  |
| [Sm L₂-M₁ and 15 others; 0.9061> | Ok         | Ok      |                                  |
| [Sm L₂-N₁ and 9 others; 0.0745>  | Ok         | Ok      |                                  |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>rem spex suitable "EDAX All" Eu Eu 20 --format markdown 

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" Eu2O3 Eu 20 --format markdown 
| Region                           | Result     | Coating | Notes                            |
|----------------------------------|------------|---------|----------------------------------|
| [Eu O₁-O₃ and 20 others; 1.7608> | Interfered | Ok      | [O K-L₂ and 1 others; 1.0000> on |
|                                  |            |         | [40,64)                          |
| [Eu M₅-N₃ and 18 others; 0.9890> | Ok         | Ok      |                                  |
| [Eu M₁-O₂ and 1 others; 0.0012>  | Ok         | Ok      |                                  |
| [Eu L₃-M₁ and 18 others; 0.9240> | Ok         | Ok      |                                  |
| [Eu L₂-N₁ and 10 others; 0.0749> | Ok         | Ok      |                                  |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" EuF3 Eu 20 --format markdown 
| Region                           | Result     | Coating | Notes                            |
|----------------------------------|------------|---------|----------------------------------|
| [Eu O₁-O₃ and 20 others; 1.7608> | Ok         | Ok      |                                  |
| [Eu M₅-N₃ and 18 others; 0.9890> | Interfered | Ok      | [F K-L₂ and 1 others; 1.0000> on |
|                                  |            |         | [54,80)                          |
| [Eu M₁-O₂ and 1 others; 0.0012>  | Ok         | Ok      |                                  |
| [Eu L₃-M₁ and 18 others; 0.9240> | Ok         | Ok      |                                  |
| [Eu L₂-N₁ and 10 others; 0.0749> | Ok         | Ok      |                                  |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" EuP5O14 Eu 20 --format markdown 
| Region                           | Result     | Coating | Notes                            |
|----------------------------------|------------|---------|----------------------------------|
| [Eu O₁-O₃ and 20 others; 1.7608> | Interfered | Ok      | [O K-L₂ and 1 others; 1.0000> on |
|                                  |            |         | [40,64), [P L₁-L₂ and 6 others;  |
|                                  |            |         | 1.0000> on [10,27)               |
| [Eu M₅-N₃ and 18 others; 0.9890> | Ok         | Ok      |                                  |
| [Eu M₁-O₂ and 1 others; 0.0012>  | Interfered | Ok      | [P K-L₂ and 3 others; 1.0000> on |
|                                  |            |         | [184,227)                        |
| [Eu L₃-M₁ and 18 others; 0.9240> | Ok         | Ok      |                                  |
| [Eu L₂-N₁ and 10 others; 0.0749> | Ok         | Ok      |                                  |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" Gd Gd 20 --format markdown 
| Region                           | Result | Coating | Notes |
|----------------------------------|--------|---------|-------|
| [Gd O₁-O₂ and 21 others; 2.0099> | Ok     | Ok      |       |
| [Gd M₅-N₃ and 18 others; 0.9900> | Ok     | Ok      |       |
| [Gd M₁-O₂ and 1 others; 0.0011>  | Ok     | Ok      |       |
| [Gd L₃-M₁ and 18 others; 0.9229> | Ok     | Ok      |       |
| [Gd L₂-N₁ and 10 others; 0.0760> | Ok     | Ok      |       |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" Gd2O3 Gd 20 --format markdown 
| Region                           | Result     | Coating | Notes                            |
|----------------------------------|------------|---------|----------------------------------|
| [Gd O₁-O₂ and 21 others; 2.0099> | Interfered | Ok      | [O K-L₂ and 1 others; 1.0000> on |
|                                  |            |         | [40,64)                          |
| [Gd M₅-N₃ and 18 others; 0.9900> | Ok         | Ok      |                                  |
| [Gd M₁-O₂ and 1 others; 0.0011>  | Ok         | Ok      |                                  |
| [Gd L₃-M₁ and 18 others; 0.9229> | Ok         | Ok      |                                  |
| [Gd L₂-N₁ and 10 others; 0.0760> | Ok         | Ok      |                                  |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" GdF3 Gd 20 --format markdown 
| Region                           | Result     | Coating | Notes                            |
|----------------------------------|------------|---------|----------------------------------|
| [Gd O₁-O₂ and 21 others; 2.0099> | Interfered | Ok      | [F K-L₂ and 1 others; 1.0000> on |
|                                  |            |         | [54,80)                          |
| [Gd M₅-N₃ and 18 others; 0.9900> | Interfered | Ok      | [F K-L₂ and 1 others; 1.0000> on |
|                                  |            |         | [54,80)                          |
| [Gd M₁-O₂ and 1 others; 0.0011>  | Ok         | Ok      |                                  |
| [Gd L₃-M₁ and 18 others; 0.9229> | Ok         | Ok      |                                  |
| [Gd L₂-N₁ and 10 others; 0.0760> | Ok         | Ok      |                                  |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" GdP5O14 Gd 20 --format markdown 
| Region                           | Result     | Coating | Notes                            |
|----------------------------------|------------|---------|----------------------------------|
| [Gd O₁-O₂ and 21 others; 2.0099> | Interfered | Ok      | [O K-L₂ and 1 others; 1.0000> on |
|                                  |            |         | [40,64), [P L₁-L₂ and 6 others;  |
|                                  |            |         | 1.0000> on [10,27)               |
| [Gd M₅-N₃ and 18 others; 0.9900> | Ok         | Ok      |                                  |
| [Gd M₁-O₂ and 1 others; 0.0011>  | Interfered | Ok      | [P K-L₂ and 3 others; 1.0000> on |
|                                  |            |         | [184,227)                        |
| [Gd L₃-M₁ and 18 others; 0.9229> | Ok         | Ok      |                                  |
| [Gd L₂-N₁ and 10 others; 0.0760> | Ok         | Ok      |                                  |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" Tb Tb 20 --format markdown 
| Region                           | Result | Coating | Notes |
|----------------------------------|--------|---------|-------|
| [Tb O₁-O₂ and 21 others; 2.0092> | Ok     | Ok      |       |
| [Tb M₅-N₃ and 18 others; 0.9908> | Ok     | Ok      |       |
| [Tb M₁-O₂ and 1 others; 0.0011>  | Ok     | Ok      |       |
| [Tb L₃-M₁ and 5 others; 0.5168>  | Ok     | Ok      |       |
| [Tb L₂-M₃ and 12 others; 0.4062> | Ok     | Ok      |       |
| [Tb L₂-N₁ and 10 others; 0.0759> | Ok     | Ok      |       |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" TbF3 Tb 20 --format markdown 
| Region                           | Result     | Coating | Notes                            |
|----------------------------------|------------|---------|----------------------------------|
| [Tb O₁-O₂ and 21 others; 2.0092> | Interfered | Ok      | [F K-L₂ and 1 others; 1.0000> on |
|                                  |            |         | [54,80)                          |
| [Tb M₅-N₃ and 18 others; 0.9908> | Ok         | Ok      |                                  |
| [Tb M₁-O₂ and 1 others; 0.0011>  | Ok         | Ok      |                                  |
| [Tb L₃-M₁ and 5 others; 0.5168>  | Ok         | Ok      |                                  |
| [Tb L₂-M₃ and 12 others; 0.4062> | Ok         | Ok      |                                  |
| [Tb L₂-N₁ and 10 others; 0.0759> | Ok         | Ok      |                                  |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" TbSi2 Tb 20 --format markdown 
| Region                           | Result     | Coating | Notes                              |
|----------------------------------|------------|---------|------------------------------------|
| [Tb O₁-O₂ and 21 others; 2.0092> | Interfered | Ok      | [Si L₁-L₂ and 5 others; 1.0000> on |
|                                  |            |         | [10,21)                            |
| [Tb M₅-N₃ and 18 others; 0.9908> | Interfered | Ok      | [Si K-L₂ and 3 others; 1.0000> on  |
|                                  |            |         | [157,195)                          |
| [Tb M₁-O₂ and 1 others; 0.0011>  | Interfered | Ok      | [Si K-L₂ and 3 others; 1.0000> on  |
|                                  |            |         | [157,195)                          |
| [Tb L₃-M₁ and 5 others; 0.5168>  | Ok         | Ok      |                                    |
| [Tb L₂-M₃ and 12 others; 0.4062> | Ok         | Ok      |                                    |
| [Tb L₂-N₁ and 10 others; 0.0759> | Ok         | Ok      |                                    |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" TbP5O14 Tb 20 --format markdown 
| Region                           | Result     | Coating | Notes                            |
|----------------------------------|------------|---------|----------------------------------|
| [Tb O₁-O₂ and 21 others; 2.0092> | Interfered | Ok      | [O K-L₂ and 1 others; 1.0000> on |
|                                  |            |         | [40,64), [P L₁-L₂ and 6 others;  |
|                                  |            |         | 1.0000> on [10,27)               |
| [Tb M₅-N₃ and 18 others; 0.9908> | Ok         | Ok      |                                  |
| [Tb M₁-O₂ and 1 others; 0.0011>  | Interfered | Ok      | [P K-L₂ and 3 others; 1.0000> on |
|                                  |            |         | [184,227)                        |
| [Tb L₃-M₁ and 5 others; 0.5168>  | Ok         | Ok      |                                  |
| [Tb L₂-M₃ and 12 others; 0.4062> | Ok         | Ok      |                                  |
| [Tb L₂-N₁ and 10 others; 0.0759> | Ok         | Ok      |                                  |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" Dy Dy 20 --format markdown 
| Region                           | Result | Coating | Notes |
|----------------------------------|--------|---------|-------|
| [Dy O₁-O₂ and 21 others; 2.0085> | Ok     | Ok      |       |
| [Dy M₄-N₂ and 2 others; 0.3269>  | Ok     | Ok      |       |
| [Dy L₁-L₃ and 15 others; 0.6645> | Ok     | Ok      |       |
| [Dy M₁-O₂ and 1 others; 0.0011>  | Ok     | Ok      |       |
| [Dy L₃-M₁ and 5 others; 0.5177>  | Ok     | Ok      |       |
| [Dy L₂-M₃ and 12 others; 0.4053> | Ok     | Ok      |       |
| [Dy L₂-N₁ and 10 others; 0.0759> | Ok     | Ok      |       |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" DyF3 Dy 20 --format markdown 
| Region                           | Result     | Coating | Notes                            |
|----------------------------------|------------|---------|----------------------------------|
| [Dy O₁-O₂ and 21 others; 2.0085> | Interfered | Ok      | [F K-L₂ and 1 others; 1.0000> on |
|                                  |            |         | [54,80)                          |
| [Dy M₄-N₂ and 2 others; 0.3269>  | Ok         | Ok      |                                  |
| [Dy L₁-L₃ and 15 others; 0.6645> | Ok         | Ok      |                                  |
| [Dy M₁-O₂ and 1 others; 0.0011>  | Ok         | Ok      |                                  |
| [Dy L₃-M₁ and 5 others; 0.5177>  | Ok         | Ok      |                                  |
| [Dy L₂-M₃ and 12 others; 0.4053> | Ok         | Ok      |                                  |
| [Dy L₂-N₁ and 10 others; 0.0759> | Ok         | Ok      |                                  |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" Dy2O3 Dy 20 --format markdown 
| Region                           | Result     | Coating | Notes                            |
|----------------------------------|------------|---------|----------------------------------|
| [Dy O₁-O₂ and 21 others; 2.0085> | Interfered | Ok      | [O K-L₂ and 1 others; 1.0000> on |
|                                  |            |         | [40,64)                          |
| [Dy M₄-N₂ and 2 others; 0.3269>  | Ok         | Ok      |                                  |
| [Dy L₁-L₃ and 15 others; 0.6645> | Ok         | Ok      |                                  |
| [Dy M₁-O₂ and 1 others; 0.0011>  | Ok         | Ok      |                                  |
| [Dy L₃-M₁ and 5 others; 0.5177>  | Ok         | Ok      |                                  |
| [Dy L₂-M₃ and 12 others; 0.4053> | Ok         | Ok      |                                  |
| [Dy L₂-N₁ and 10 others; 0.0759> | Ok         | Ok      |                                  |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" DyP5O14 Dy 20 --format markdown 
| Region                           | Result     | Coating | Notes                            |
|----------------------------------|------------|---------|----------------------------------|
| [Dy O₁-O₂ and 21 others; 2.0085> | Interfered | Ok      | [O K-L₂ and 1 others; 1.0000> on |
|                                  |            |         | [40,64), [P L₁-L₂ and 6 others;  |
|                                  |            |         | 1.0000> on [10,27)               |
| [Dy M₄-N₂ and 2 others; 0.3269>  | Ok         | Ok      |                                  |
| [Dy L₁-L₃ and 15 others; 0.6645> | Interfered | Ok      | [P K-L₂ and 3 others; 1.0000> on |
|                                  |            |         | [184,227)                        |
| [Dy M₁-O₂ and 1 others; 0.0011>  | Interfered | Ok      | [P K-L₂ and 3 others; 1.0000> on |
|                                  |            |         | [184,227)                        |
| [Dy L₃-M₁ and 5 others; 0.5177>  | Ok         | Ok      |                                  |
| [Dy L₂-M₃ and 12 others; 0.4053> | Ok         | Ok      |                                  |
| [Dy L₂-N₁ and 10 others; 0.0759> | Ok         | Ok      |                                  |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" Ho Ho 20 --format markdown 
| Region                           | Result | Coating | Notes |
|----------------------------------|--------|---------|-------|
| [Ho O₁-O₂ and 21 others; 2.0080> | Ok     | Ok      |       |
| [Ho M₅-N₃ and 18 others; 0.9921> | Ok     | Ok      |       |
| [Ho M₁-O₂ and 1 others; 0.0010>  | Ok     | Ok      |       |
| [Ho L₃-M₁ and 5 others; 0.5147>  | Ok     | Ok      |       |
| [Ho L₂-M₃ and 12 others; 0.4077> | Ok     | Ok      |       |
| [Ho L₂-N₁ and 10 others; 0.0765> | Ok     | Ok      |       |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" HoF3 Ho 20 --format markdown 
| Region                           | Result     | Coating | Notes                            |
|----------------------------------|------------|---------|----------------------------------|
| [Ho O₁-O₂ and 21 others; 2.0080> | Interfered | Ok      | [F K-L₂ and 1 others; 1.0000> on |
|                                  |            |         | [54,80)                          |
| [Ho M₅-N₃ and 18 others; 0.9921> | Ok         | Ok      |                                  |
| [Ho M₁-O₂ and 1 others; 0.0010>  | Ok         | Ok      |                                  |
| [Ho L₃-M₁ and 5 others; 0.5147>  | Ok         | Ok      |                                  |
| [Ho L₂-M₃ and 12 others; 0.4077> | Ok         | Ok      |                                  |
| [Ho L₂-N₁ and 10 others; 0.0765> | Ok         | Ok      |                                  |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" Ho2O3 Ho 20 --format markdown 
| Region                           | Result     | Coating | Notes                            |
|----------------------------------|------------|---------|----------------------------------|
| [Ho O₁-O₂ and 21 others; 2.0080> | Interfered | Ok      | [O K-L₂ and 1 others; 1.0000> on |
|                                  |            |         | [40,64)                          |
| [Ho M₅-N₃ and 18 others; 0.9921> | Ok         | Ok      |                                  |
| [Ho M₁-O₂ and 1 others; 0.0010>  | Ok         | Ok      |                                  |
| [Ho L₃-M₁ and 5 others; 0.5147>  | Ok         | Ok      |                                  |
| [Ho L₂-M₃ and 12 others; 0.4077> | Ok         | Ok      |                                  |
| [Ho L₂-N₁ and 10 others; 0.0765> | Ok         | Ok      |                                  |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" HoP5O14 Ho 20 --format markdown 
| Region                           | Result     | Coating | Notes                            |
|----------------------------------|------------|---------|----------------------------------|
| [Ho O₁-O₂ and 21 others; 2.0080> | Interfered | Ok      | [O K-L₂ and 1 others; 1.0000> on |
|                                  |            |         | [40,64), [P L₁-L₂ and 6 others;  |
|                                  |            |         | 1.0000> on [10,27)               |
| [Ho M₅-N₃ and 18 others; 0.9921> | Interfered | Ok      | [P K-L₂ and 3 others; 1.0000> on |
|                                  |            |         | [184,227)                        |
| [Ho M₁-O₂ and 1 others; 0.0010>  | Interfered | Ok      | [P K-L₂ and 3 others; 1.0000> on |
|                                  |            |         | [184,227)                        |
| [Ho L₃-M₁ and 5 others; 0.5147>  | Ok         | Ok      |                                  |
| [Ho L₂-M₃ and 12 others; 0.4077> | Ok         | Ok      |                                  |
| [Ho L₂-N₁ and 10 others; 0.0765> | Ok         | Ok      |                                  |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" Er Er 20 --format markdown 
| Region                           | Result | Coating | Notes |
|----------------------------------|--------|---------|-------|
| [Er O₁-O₂ and 21 others; 2.0075> | Ok     | Ok      |       |
| [Er M₄-N₂ and 18 others; 0.9926> | Ok     | Ok      |       |
| [Er M₁-O₂ and 1 others; 0.0010>  | Ok     | Ok      |       |
| [Er L₃-M₁ and 2 others; 0.0195>  | Ok     | Ok      |       |
| [Er L₃-M₄ and 2 others; 0.4955>  | Ok     | Ok      |       |
| [Er L₂-M₃ and 12 others; 0.4072> | Ok     | Ok      |       |
| [Er L₂-N₁ and 10 others; 0.0766> | Ok     | Ok      |       |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" ErF3 Er 20 --format markdown 
| Region                           | Result     | Coating | Notes                            |
|----------------------------------|------------|---------|----------------------------------|
| [Er O₁-O₂ and 21 others; 2.0075> | Interfered | Ok      | [F K-L₂ and 1 others; 1.0000> on |
|                                  |            |         | [54,80)                          |
| [Er M₄-N₂ and 18 others; 0.9926> | Ok         | Ok      |                                  |
| [Er M₁-O₂ and 1 others; 0.0010>  | Ok         | Ok      |                                  |
| [Er L₃-M₁ and 2 others; 0.0195>  | Ok         | Ok      |                                  |
| [Er L₃-M₄ and 2 others; 0.4955>  | Ok         | Ok      |                                  |
| [Er L₂-M₃ and 12 others; 0.4072> | Ok         | Ok      |                                  |
| [Er L₂-N₁ and 10 others; 0.0766> | Ok         | Ok      |                                  |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" Er2O3 Er 20 --format markdown 
| Region                           | Result     | Coating | Notes                            |
|----------------------------------|------------|---------|----------------------------------|
| [Er O₁-O₂ and 21 others; 2.0075> | Interfered | Ok      | [O K-L₂ and 1 others; 1.0000> on |
|                                  |            |         | [40,64)                          |
| [Er M₄-N₂ and 18 others; 0.9926> | Ok         | Ok      |                                  |
| [Er M₁-O₂ and 1 others; 0.0010>  | Ok         | Ok      |                                  |
| [Er L₃-M₁ and 2 others; 0.0195>  | Ok         | Ok      |                                  |
| [Er L₃-M₄ and 2 others; 0.4955>  | Ok         | Ok      |                                  |
| [Er L₂-M₃ and 12 others; 0.4072> | Ok         | Ok      |                                  |
| [Er L₂-N₁ and 10 others; 0.0766> | Ok         | Ok      |                                  |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" ErP5O14 Er 20 --format markdown 
| Region                           | Result     | Coating | Notes                            |
|----------------------------------|------------|---------|----------------------------------|
| [Er O₁-O₂ and 21 others; 2.0075> | Interfered | Ok      | [O K-L₂ and 1 others; 1.0000> on |
|                                  |            |         | [40,64), [P L₁-L₂ and 6 others;  |
|                                  |            |         | 1.0000> on [10,27)               |
| [Er M₄-N₂ and 18 others; 0.9926> | Interfered | Ok      | [P K-L₂ and 3 others; 1.0000> on |
|                                  |            |         | [184,227)                        |
| [Er M₁-O₂ and 1 others; 0.0010>  | Interfered | Ok      | [P K-L₂ and 3 others; 1.0000> on |
|                                  |            |         | [184,227)                        |
| [Er L₃-M₁ and 2 others; 0.0195>  | Ok         | Ok      |                                  |
| [Er L₃-M₄ and 2 others; 0.4955>  | Ok         | Ok      |                                  |
| [Er L₂-M₃ and 12 others; 0.4072> | Ok         | Ok      |                                  |
| [Er L₂-N₁ and 10 others; 0.0766> | Ok         | Ok      |                                  |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" Tm Tm 20 --format markdown 
| Region                           | Result | Coating | Notes |
|----------------------------------|--------|---------|-------|
| [Tm O₁-O₂ and 21 others; 2.0071> | Ok     | Ok      |       |
| [Tm M₄-N₂ and 2 others; 0.1851>  | Ok     | Ok      |       |
| [Tm M₃-N₁ and 15 others; 0.8079> | Ok     | Ok      |       |
| [Tm M₁-O₂ and 1 others; 0.0010>  | Ok     | Ok      |       |
| [Tm L₃-M₁ and 2 others; 0.0199>  | Ok     | Ok      |       |
| [Tm L₃-M₄ and 2 others; 0.4991>  | Ok     | Ok      |       |
| [Tm L₂-M₃ and 12 others; 0.4042> | Ok     | Ok      |       |
| [Tm L₂-N₁ and 10 others; 0.0757> | Ok     | Ok      |       |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" TmF3 Tm 20 --format markdown 
| Region                           | Result     | Coating | Notes                            |
|----------------------------------|------------|---------|----------------------------------|
| [Tm O₁-O₂ and 21 others; 2.0071> | Interfered | Ok      | [F K-L₂ and 1 others; 1.0000> on |
|                                  |            |         | [54,80)                          |
| [Tm M₄-N₂ and 2 others; 0.1851>  | Ok         | Ok      |                                  |
| [Tm M₃-N₁ and 15 others; 0.8079> | Ok         | Ok      |                                  |
| [Tm M₁-O₂ and 1 others; 0.0010>  | Ok         | Ok      |                                  |
| [Tm L₃-M₁ and 2 others; 0.0199>  | Ok         | Ok      |                                  |
| [Tm L₃-M₄ and 2 others; 0.4991>  | Ok         | Ok      |                                  |
| [Tm L₂-M₃ and 12 others; 0.4042> | Ok         | Ok      |                                  |
| [Tm L₂-N₁ and 10 others; 0.0757> | Ok         | Ok      |                                  |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" TmSi2 Tm 20 --format markdown 
| Region                           | Result     | Coating | Notes                              |
|----------------------------------|------------|---------|------------------------------------|
| [Tm O₁-O₂ and 21 others; 2.0071> | Interfered | Ok      | [Si L₁-L₂ and 5 others; 1.0000> on |
|                                  |            |         | [10,21)                            |
| [Tm M₄-N₂ and 2 others; 0.1851>  | Ok         | Ok      |                                    |
| [Tm M₃-N₁ and 15 others; 0.8079> | Interfered | Ok      | [Si K-L₂ and 3 others; 1.0000> on  |
|                                  |            |         | [157,195)                          |
| [Tm M₁-O₂ and 1 others; 0.0010>  | Ok         | Ok      |                                    |
| [Tm L₃-M₁ and 2 others; 0.0199>  | Ok         | Ok      |                                    |
| [Tm L₃-M₄ and 2 others; 0.4991>  | Ok         | Ok      |                                    |
| [Tm L₂-M₃ and 12 others; 0.4042> | Ok         | Ok      |                                    |
| [Tm L₂-N₁ and 10 others; 0.0757> | Ok         | Ok      |                                    |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" TmP5O14 Tm 20 --format markdown 
| Region                           | Result     | Coating | Notes                            |
|----------------------------------|------------|---------|----------------------------------|
| [Tm O₁-O₂ and 21 others; 2.0071> | Interfered | Ok      | [O K-L₂ and 1 others; 1.0000> on |
|                                  |            |         | [40,64), [P L₁-L₂ and 6 others;  |
|                                  |            |         | 1.0000> on [10,27)               |
| [Tm M₄-N₂ and 2 others; 0.1851>  | Ok         | Ok      |                                  |
| [Tm M₃-N₁ and 15 others; 0.8079> | Interfered | Ok      | [P K-L₂ and 3 others; 1.0000> on |
|                                  |            |         | [184,227)                        |
| [Tm M₁-O₂ and 1 others; 0.0010>  | Interfered | Ok      | [P K-L₂ and 3 others; 1.0000> on |
|                                  |            |         | [184,227)                        |
| [Tm L₃-M₁ and 2 others; 0.0199>  | Ok         | Ok      |                                  |
| [Tm L₃-M₄ and 2 others; 0.4991>  | Ok         | Ok      |                                  |
| [Tm L₂-M₃ and 12 others; 0.4042> | Ok         | Ok      |                                  |
| [Tm L₂-N₁ and 10 others; 0.0757> | Ok         | Ok      |                                  |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" Yb Yb 20 --format markdown 
| Region                           | Result | Coating | Notes |
|----------------------------------|--------|---------|-------|
| [Yb O₁-O₂ and 20 others; 2.0068> | Ok     | Ok      |       |
| [Yb M₄-N₂ and 18 others; 0.9932> | Ok     | Ok      |       |
| [Yb M₁-O₂ and 1 others; 0.0010>  | Ok     | Ok      |       |
| [Yb L₃-M₁ and 2 others; 0.0209>  | Ok     | Ok      |       |
| [Yb L₃-M₄ and 2 others; 0.5142>  | Ok     | Ok      |       |
| [Yb L₂-M₃ and 13 others; 0.3912> | Ok     | Ok      |       |
| [Yb L₂-N₁ and 10 others; 0.0728> | Ok     | Ok      |       |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" YbF3 Yb 20 --format markdown 
| Region                           | Result     | Coating | Notes                            |
|----------------------------------|------------|---------|----------------------------------|
| [Yb O₁-O₂ and 20 others; 2.0068> | Interfered | Ok      | [F K-L₂ and 1 others; 1.0000> on |
|                                  |            |         | [54,80)                          |
| [Yb M₄-N₂ and 18 others; 0.9932> | Ok         | Ok      |                                  |
| [Yb M₁-O₂ and 1 others; 0.0010>  | Ok         | Ok      |                                  |
| [Yb L₃-M₁ and 2 others; 0.0209>  | Ok         | Ok      |                                  |
| [Yb L₃-M₄ and 2 others; 0.5142>  | Ok         | Ok      |                                  |
| [Yb L₂-M₃ and 13 others; 0.3912> | Ok         | Ok      |                                  |
| [Yb L₂-N₁ and 10 others; 0.0728> | Ok         | Ok      |                                  |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" YbP5O14 Yb 20 --format markdown 
| Region                           | Result     | Coating | Notes                            |
|----------------------------------|------------|---------|----------------------------------|
| [Yb O₁-O₂ and 20 others; 2.0068> | Interfered | Ok      | [O K-L₂ and 1 others; 1.0000> on |
|                                  |            |         | [40,64), [P L₁-L₂ and 6 others;  |
|                                  |            |         | 1.0000> on [10,27)               |
| [Yb M₄-N₂ and 18 others; 0.9932> | Interfered | Ok      | [P K-L₂ and 3 others; 1.0000> on |
|                                  |            |         | [184,227)                        |
| [Yb M₁-O₂ and 1 others; 0.0010>  | Ok         | Ok      |                                  |
| [Yb L₃-M₁ and 2 others; 0.0209>  | Ok         | Ok      |                                  |
| [Yb L₃-M₄ and 2 others; 0.5142>  | Ok         | Ok      |                                  |
| [Yb L₂-M₃ and 13 others; 0.3912> | Ok         | Ok      |                                  |
| [Yb L₂-N₁ and 10 others; 0.0728> | Ok         | Ok      |                                  |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" Lu Lu 20 --format markdown 
| Region                           | Result | Coating | Notes |
|----------------------------------|--------|---------|-------|
| [Lu O₁-O₂ and 23 others; 1.9933> | Ok     | Ok      |       |
| [Lu M₅-N₃ and 2 others; 0.1341>  | Ok     | Ok      |       |
| [Lu M₃-N₁ and 17 others; 0.8594> | Ok     | Ok      |       |
| [Lu M₁-O₂ and 1 others; 0.0010>  | Ok     | Ok      |       |
| [Lu L₃-M₁ and 2 others; 0.0205>  | Ok     | Ok      |       |
| [Lu L₃-M₄ and 2 others; 0.5018>  | Ok     | Ok      |       |
| [Lu L₂-M₃ and 15 others; 0.4010> | Ok     | Ok      |       |
| [Lu L₂-N₁ and 11 others; 0.0756> | Ok     | Ok      |       |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" LuP5O14 Lu 20 --format markdown 
| Region                           | Result     | Coating | Notes                            |
|----------------------------------|------------|---------|----------------------------------|
| [Lu O₁-O₂ and 23 others; 1.9933> | Interfered | Ok      | [O K-L₂ and 1 others; 1.0000> on |
|                                  |            |         | [40,64), [P L₁-L₂ and 6 others;  |
|                                  |            |         | 1.0000> on [10,27)               |
| [Lu M₅-N₃ and 2 others; 0.1341>  | Ok         | Ok      |                                  |
| [Lu M₃-N₁ and 17 others; 0.8594> | Interfered | Ok      | [P K-L₂ and 3 others; 1.0000> on |
|                                  |            |         | [184,227)                        |
| [Lu M₁-O₂ and 1 others; 0.0010>  | Ok         | Ok      |                                  |
| [Lu L₃-M₁ and 2 others; 0.0205>  | Ok         | Ok      |                                  |
| [Lu L₃-M₄ and 2 others; 0.5018>  | Ok         | Ok      |                                  |
| [Lu L₂-M₃ and 15 others; 0.4010> | Ok         | Ok      |                                  |
| [Lu L₂-N₁ and 11 others; 0.0756> | Ok         | Ok      |                                  |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" Hf Hf 20 --format markdown 
| Region                           | Result | Coating | Notes |
|----------------------------------|--------|---------|-------|
| [Hf O₁-O₂ and 25 others; 2.0061> | Ok     | Ok      |       |
| [Hf M₄-N₂ and 2 others; 0.1185>  | Ok     | Ok      |       |
| [Hf M₃-N₁ and 18 others; 0.8754> | Ok     | Ok      |       |
| [Hf M₁-O₂ and 1 others; 0.0009>  | Ok     | Ok      |       |
| [Hf L₃-M₁ and 2 others; 0.0209>  | Ok     | Ok      |       |
| [Hf L₃-M₄ and 2 others; 0.5015>  | Ok     | Ok      |       |
| [Hf L₂-M₃ and 15 others; 0.4003> | Ok     | Ok      |       |
| [Hf L₂-N₁ and 11 others; 0.0763> | Ok     | Ok      |       |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" HfO2 Hf 20 --format markdown 
| Region                           | Result     | Coating | Notes                            |
|----------------------------------|------------|---------|----------------------------------|
| [Hf O₁-O₂ and 25 others; 2.0061> | Interfered | Ok      | [O K-L₂ and 1 others; 1.0000> on |
|                                  |            |         | [40,64)                          |
| [Hf M₄-N₂ and 2 others; 0.1185>  | Ok         | Ok      |                                  |
| [Hf M₃-N₁ and 18 others; 0.8754> | Ok         | Ok      |                                  |
| [Hf M₁-O₂ and 1 others; 0.0009>  | Ok         | Ok      |                                  |
| [Hf L₃-M₁ and 2 others; 0.0209>  | Ok         | Ok      |                                  |
| [Hf L₃-M₄ and 2 others; 0.5015>  | Ok         | Ok      |                                  |
| [Hf L₂-M₃ and 15 others; 0.4003> | Ok         | Ok      |                                  |
| [Hf L₂-N₁ and 11 others; 0.0763> | Ok         | Ok      |                                  |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" Ta Ta 20 --format markdown 
| Region                           | Result | Coating | Notes |
|----------------------------------|--------|---------|-------|
| [Ta O₁-O₂ and 26 others; 2.0058> | Ok     | Ok      |       |
| [Ta M₄-N₂ and 2 others; 0.1059>  | Ok     | Ok      |       |
| [Ta M₃-N₁ and 18 others; 0.8883> | Ok     | Ok      |       |
| [Ta M₁-O₂ and 1 others; 0.0009>  | Ok     | Ok      |       |
| [Ta L₃-M₁ and 1 others; 0.0210>  | Ok     | Ok      |       |
| [Ta L₃-M₃; 0.0003>               | Ok     | Ok      |       |
| [Ta L₃-M₄ and 2 others; 0.5031>  | Ok     | Ok      |       |
| [Ta L₂-M₃ and 15 others; 0.3979> | Ok     | Ok      |       |
| [Ta L₂-N₁ and 11 others; 0.0767> | Ok     | Ok      |       |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" Li2Ta2O6 Ta 20 --format markdown 
| Region                           | Result     | Coating | Notes                                  |
|----------------------------------|------------|---------|----------------------------------------|
| [Ta O₁-O₂ and 26 others; 2.0058> | Interfered | Ok      | [Li K-L₁; 1.0000> on [10,15), [O K-L₂  |
|                                  |            |         | and 1 others; 1.0000> on [40,64)       |
| [Ta M₄-N₂ and 2 others; 0.1059>  | Ok         | Ok      |                                        |
| [Ta M₃-N₁ and 18 others; 0.8883> | Ok         | Ok      |                                        |
| [Ta M₁-O₂ and 1 others; 0.0009>  | Ok         | Ok      |                                        |
| [Ta L₃-M₁ and 1 others; 0.0210>  | Ok         | Ok      |                                        |
| [Ta L₃-M₃; 0.0003>               | Ok         | Ok      |                                        |
| [Ta L₃-M₄ and 2 others; 0.5031>  | Ok         | Ok      |                                        |
| [Ta L₂-M₃ and 15 others; 0.3979> | Ok         | Ok      |                                        |
| [Ta L₂-N₁ and 11 others; 0.0767> | Ok         | Ok      |                                        |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" TaN Ta 20 --format markdown 
| Region                           | Result     | Coating | Notes                            |
|----------------------------------|------------|---------|----------------------------------|
| [Ta O₁-O₂ and 26 others; 2.0058> | Interfered | Ok      | [N K-L₂ and 1 others; 1.0000> on |
|                                  |            |         | [27,51)                          |
| [Ta M₄-N₂ and 2 others; 0.1059>  | Ok         | Ok      |                                  |
| [Ta M₃-N₁ and 18 others; 0.8883> | Ok         | Ok      |                                  |
| [Ta M₁-O₂ and 1 others; 0.0009>  | Ok         | Ok      |                                  |
| [Ta L₃-M₁ and 1 others; 0.0210>  | Ok         | Ok      |                                  |
| [Ta L₃-M₃; 0.0003>               | Ok         | Ok      |                                  |
| [Ta L₃-M₄ and 2 others; 0.5031>  | Ok         | Ok      |                                  |
| [Ta L₂-M₃ and 15 others; 0.3979> | Ok         | Ok      |                                  |
| [Ta L₂-N₁ and 11 others; 0.0767> | Ok         | Ok      |                                  |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" Ta2O5 Ta 20 --format markdown 
| Region                           | Result     | Coating | Notes                            |
|----------------------------------|------------|---------|----------------------------------|
| [Ta O₁-O₂ and 26 others; 2.0058> | Interfered | Ok      | [O K-L₂ and 1 others; 1.0000> on |
|                                  |            |         | [40,64)                          |
| [Ta M₄-N₂ and 2 others; 0.1059>  | Ok         | Ok      |                                  |
| [Ta M₃-N₁ and 18 others; 0.8883> | Ok         | Ok      |                                  |
| [Ta M₁-O₂ and 1 others; 0.0009>  | Ok         | Ok      |                                  |
| [Ta L₃-M₁ and 1 others; 0.0210>  | Ok         | Ok      |                                  |
| [Ta L₃-M₃; 0.0003>               | Ok         | Ok      |                                  |
| [Ta L₃-M₄ and 2 others; 0.5031>  | Ok         | Ok      |                                  |
| [Ta L₂-M₃ and 15 others; 0.3979> | Ok         | Ok      |                                  |
| [Ta L₂-N₁ and 11 others; 0.0767> | Ok         | Ok      |                                  |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" TaSi2 Ta 20 --format markdown 
| Region                           | Result     | Coating | Notes                              |
|----------------------------------|------------|---------|------------------------------------|
| [Ta O₁-O₂ and 26 others; 2.0058> | Interfered | Ok      | [Si L₁-L₂ and 5 others; 1.0000> on |
|                                  |            |         | [10,21)                            |
| [Ta M₄-N₂ and 2 others; 0.1059>  | Ok         | Ok      |                                    |
| [Ta M₃-N₁ and 18 others; 0.8883> | Interfered | Ok      | [Si K-L₂ and 3 others; 1.0000> on  |
|                                  |            |         | [157,195)                          |
| [Ta M₁-O₂ and 1 others; 0.0009>  | Ok         | Ok      |                                    |
| [Ta L₃-M₁ and 1 others; 0.0210>  | Ok         | Ok      |                                    |
| [Ta L₃-M₃; 0.0003>               | Ok         | Ok      |                                    |
| [Ta L₃-M₄ and 2 others; 0.5031>  | Ok         | Ok      |                                    |
| [Ta L₂-M₃ and 15 others; 0.3979> | Ok         | Ok      |                                    |
| [Ta L₂-N₁ and 11 others; 0.0767> | Ok         | Ok      |                                    |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" W W 20 --format markdown 
| Region                          | Result | Coating | Notes |
|---------------------------------|--------|---------|-------|
| [W O₃-O₅ and 27 others; 2.0055> | Ok     | Ok      |       |
| [W M₄-N₂ and 2 others; 0.0948>  | Ok     | Ok      |       |
| [W M₃-N₁ and 18 others; 0.8997> | Ok     | Ok      |       |
| [W M₁-O₂ and 1 others; 0.0009>  | Ok     | Ok      |       |
| [W L₃-M₁ and 1 others; 0.0214>  | Ok     | Ok      |       |
| [W L₃-M₃; 0.0003>               | Ok     | Ok      |       |
| [W L₃-M₄ and 2 others; 0.5044>  | Ok     | Ok      |       |
| [W L₂-M₃ and 15 others; 0.3957> | Ok     | Ok      |       |
| [W L₂-N₁ and 11 others; 0.0772> | Ok     | Ok      |       |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" CaWO4 W 20 --format markdown 
| Region                          | Result     | Coating | Notes                             |
|---------------------------------|------------|---------|-----------------------------------|
| [W O₃-O₅ and 27 others; 2.0055> | Interfered | Ok      | [O K-L₂ and 1 others; 1.0000> on  |
|                                 |            |         | [40,64), [Ca L₁-L₂ and 10 others; |
|                                 |            |         | 1.0000> on [10,52)                |
| [W M₄-N₂ and 2 others; 0.0948>  | Ok         | Ok      |                                   |
| [W M₃-N₁ and 18 others; 0.8997> | Ok         | Ok      |                                   |
| [W M₁-O₂ and 1 others; 0.0009>  | Ok         | Ok      |                                   |
| [W L₃-M₁ and 1 others; 0.0214>  | Ok         | Ok      |                                   |
| [W L₃-M₃; 0.0003>               | Ok         | Ok      |                                   |
| [W L₃-M₄ and 2 others; 0.5044>  | Ok         | Ok      |                                   |
| [W L₂-M₃ and 15 others; 0.3957> | Ok         | Ok      |                                   |
| [W L₂-N₁ and 11 others; 0.0772> | Ok         | Ok      |                                   |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" WSi2 W 20 --format markdown 
| Region                          | Result     | Coating | Notes                              |
|---------------------------------|------------|---------|------------------------------------|
| [W O₃-O₅ and 27 others; 2.0055> | Interfered | Ok      | [Si L₁-L₂ and 5 others; 1.0000> on |
|                                 |            |         | [10,21)                            |
| [W M₄-N₂ and 2 others; 0.0948>  | Ok         | Ok      |                                    |
| [W M₃-N₁ and 18 others; 0.8997> | Interfered | Ok      | [Si K-L₂ and 3 others; 1.0000> on  |
|                                 |            |         | [157,195)                          |
| [W M₁-O₂ and 1 others; 0.0009>  | Ok         | Ok      |                                    |
| [W L₃-M₁ and 1 others; 0.0214>  | Ok         | Ok      |                                    |
| [W L₃-M₃; 0.0003>               | Ok         | Ok      |                                    |
| [W L₃-M₄ and 2 others; 0.5044>  | Ok         | Ok      |                                    |
| [W L₂-M₃ and 15 others; 0.3957> | Ok         | Ok      |                                    |
| [W L₂-N₁ and 11 others; 0.0772> | Ok         | Ok      |                                    |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" WC W 20 --format markdown 
| Region                          | Result     | Coating | Notes                            |
|---------------------------------|------------|---------|----------------------------------|
| [W O₃-O₅ and 27 others; 2.0055> | Interfered | Ok      | [C K-L₃ and 1 others; 1.0000> on |
|                                 |            |         | [15,38)                          |
| [W M₄-N₂ and 2 others; 0.0948>  | Ok         | Ok      |                                  |
| [W M₃-N₁ and 18 others; 0.8997> | Ok         | Ok      |                                  |
| [W M₁-O₂ and 1 others; 0.0009>  | Ok         | Ok      |                                  |
| [W L₃-M₁ and 1 others; 0.0214>  | Ok         | Ok      |                                  |
| [W L₃-M₃; 0.0003>               | Ok         | Ok      |                                  |
| [W L₃-M₄ and 2 others; 0.5044>  | Ok         | Ok      |                                  |
| [W L₂-M₃ and 15 others; 0.3957> | Ok         | Ok      |                                  |
| [W L₂-N₁ and 11 others; 0.0772> | Ok         | Ok      |                                  |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" Re Re 20 --format markdown 
| Region                           | Result | Coating | Notes |
|----------------------------------|--------|---------|-------|
| [Re O₃-O₅ and 27 others; 1.9958> | Ok     | Ok      |       |
| [Re M₄-N₂ and 2 others; 0.0849>  | Ok     | Ok      |       |
| [Re M₃-N₁ and 18 others; 0.9098> | Ok     | Ok      |       |
| [Re M₁-O₂ and 1 others; 0.0009>  | Ok     | Ok      |       |
| [Re L₃-M₁ and 1 others; 0.0218>  | Ok     | Ok      |       |
| [Re L₃-M₃; 0.0003>               | Ok     | Ok      |       |
| [Re L₃-M₄ and 2 others; 0.5051>  | Ok     | Ok      |       |
| [Re L₂-M₃ and 15 others; 0.3938> | Ok     | Ok      |       |
| [Re L₂-N₁ and 11 others; 0.0780> | Ok     | Ok      |       |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" Os Os 20 --format markdown 
| Region                           | Result | Coating | Notes |
|----------------------------------|--------|---------|-------|
| [Os O₁-O₂ and 28 others; 2.0050> | Ok     | Ok      |       |
| [Os M₄-N₂ and 2 others; 0.0766>  | Ok     | Ok      |       |
| [Os M₃-N₁ and 20 others; 0.9193> | Ok     | Ok      |       |
| [Os L₃-M₁ and 1 others; 0.0222>  | Ok     | Ok      |       |
| [Os L₃-M₃; 0.0003>               | Ok     | Ok      |       |
| [Os L₃-M₄ and 2 others; 0.5051>  | Ok     | Ok      |       |
| [Os L₂-M₃ and 15 others; 0.3921> | Ok     | Ok      |       |
| [Os L₂-N₁ and 11 others; 0.0792> | Ok     | Ok      |       |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" Ir Ir 20 --format markdown 
| Region                           | Result | Coating | Notes |
|----------------------------------|--------|---------|-------|
| [Ir O₁-O₂ and 26 others; 2.0048> | Ok     | Ok      |       |
| [Ir M₄-N₂ and 2 others; 0.0697>  | Ok     | Ok      |       |
| [Ir M₃-N₁ and 20 others; 0.9265> | Ok     | Ok      |       |
| [Ir L₃-M₁ and 1 others; 0.0226>  | Ok     | Ok      |       |
| [Ir L₃-M₃; 0.0003>               | Ok     | Ok      |       |
| [Ir L₃-M₄ and 2 others; 0.5032>  | Ok     | Ok      |       |
| [Ir L₂-M₃ and 15 others; 0.3921> | Ok     | Ok      |       |
| [Ir L₂-N₁ and 11 others; 0.0808> | Ok     | Ok      |       |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" Pt Pt 20 --format markdown 
| Region                           | Result | Coating | Notes |
|----------------------------------|--------|---------|-------|
| [Pt O₁-O₂ and 32 others; 2.0046> | Ok     | Ok      |       |
| [Pt M₄-N₂ and 24 others; 0.9964> | Ok     | Ok      |       |
| [Pt L₃-M₁ and 1 others; 0.0229>  | Ok     | Ok      |       |
| [Pt L₃-M₃; 0.0003>               | Ok     | Ok      |       |
| [Pt L₃-M₄ and 1 others; 0.4955>  | Ok     | Ok      |       |
| [Pt L₂-M₁; 0.0053>               | Ok     | Ok      |       |
| [Pt L₂-M₃ and 16 others; 0.3925> | Ok     | Ok      |       |
| [Pt L₂-N₁ and 11 others; 0.0823> | Ok     | Ok      |       |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" Au Au 20 --format markdown 
| Region                           | Result | Coating | Notes |
|----------------------------------|--------|---------|-------|
| [Au O₁-O₂ and 33 others; 2.0045> | Ok     | Ok      |       |
| [Au M₄-N₂ and 24 others; 0.9966> | Ok     | Ok      |       |
| [Au L₃-M₁ and 1 others; 0.0235>  | Ok     | Ok      |       |
| [Au L₃-M₃; 0.0003>               | Ok     | Ok      |       |
| [Au L₃-M₄ and 1 others; 0.4986>  | Ok     | Ok      |       |
| [Au L₂-M₁; 0.0051>               | Ok     | Ok      |       |
| [Au L₂-M₃ and 16 others; 0.3872> | Ok     | Ok      |       |
| [Au L₂-N₁ and 12 others; 0.0840> | Ok     | Ok      |       |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>rem spex suitable "EDAX All" Hg Hg 20 --format markdown 

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" HgO Hg 20 --format markdown 
| Region                           | Result     | Coating | Notes                            |
|----------------------------------|------------|---------|----------------------------------|
| [Hg O₁-O₂ and 33 others; 2.0044> | Interfered | Ok      | [O K-L₂ and 1 others; 1.0000> on |
|                                  |            |         | [40,64)                          |
| [Hg M₄-N₂ and 25 others; 0.9969> | Ok         | Ok      |                                  |
| [Hg L₃-M₁ and 1 others; 0.0239>  | Ok         | Ok      |                                  |
| [Hg L₃-M₃; 0.0003>               | Ok         | Ok      |                                  |
| [Hg L₃-M₄ and 1 others; 0.4973>  | Ok         | Ok      |                                  |
| [Hg L₂-M₁; 0.0051>               | Ok         | Ok      |                                  |
| [Hg L₂-M₃ and 16 others; 0.3865> | Ok         | Ok      |                                  |
| [Hg L₂-N₁ and 12 others; 0.0855> | Ok         | Ok      |                                  |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" HgTe Hg 20 --format markdown 
| Region                           | Result     | Coating | Notes                               |
|----------------------------------|------------|---------|-------------------------------------|
| [Hg O₁-O₂ and 33 others; 2.0044> | Interfered | Ok      | [Te N₅-O₃ and 33 others; 1.9977> on |
|                                  |            |         | [10,107)                            |
| [Hg M₄-N₂ and 25 others; 0.9969> | Interfered | Ok      | [Te L₃-M₁ and 24 others; 0.9991> on |
|                                  |            |         | [317,506)                           |
| [Hg L₃-M₁ and 1 others; 0.0239>  | Ok         | Ok      |                                     |
| [Hg L₃-M₃; 0.0003>               | Ok         | Ok      |                                     |
| [Hg L₃-M₄ and 1 others; 0.4973>  | Ok         | Ok      |                                     |
| [Hg L₂-M₁; 0.0051>               | Ok         | Ok      |                                     |
| [Hg L₂-M₃ and 16 others; 0.3865> | Ok         | Ok      |                                     |
| [Hg L₂-N₁ and 12 others; 0.0855> | Ok         | Ok      |                                     |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" HgS Hg 20 --format markdown 
| Region                           | Result     | Coating | Notes                             |
|----------------------------------|------------|---------|-----------------------------------|
| [Hg O₁-O₂ and 33 others; 2.0044> | Interfered | Ok      | [S L₁-L₂ and 7 others; 1.0000> on |
|                                  |            |         | [10,31)                           |
| [Hg M₄-N₂ and 25 others; 0.9969> | Interfered | Ok      | [S K-L₂ and 3 others; 1.0000> on  |
|                                  |            |         | [213,261)                         |
| [Hg L₃-M₁ and 1 others; 0.0239>  | Ok         | Ok      |                                   |
| [Hg L₃-M₃; 0.0003>               | Ok         | Ok      |                                   |
| [Hg L₃-M₄ and 1 others; 0.4973>  | Ok         | Ok      |                                   |
| [Hg L₂-M₁; 0.0051>               | Ok         | Ok      |                                   |
| [Hg L₂-M₃ and 16 others; 0.3865> | Ok         | Ok      |                                   |
| [Hg L₂-N₁ and 12 others; 0.0855> | Ok         | Ok      |                                   |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" Tl Tl 20 --format markdown 
| Region                           | Result | Coating | Notes |
|----------------------------------|--------|---------|-------|
| [Tl O₁-O₂ and 39 others; 2.0043> | Ok     | Ok      |       |
| [Tl M₄-N₂ and 23 others; 0.9962> | Ok     | Ok      |       |
| [Tl M₁-O₂ and 1 others; 0.0008>  | Ok     | Ok      |       |
| [Tl L₃-M₁ and 1 others; 0.0243>  | Ok     | Ok      |       |
| [Tl L₃-M₃; 0.0003>               | Ok     | Ok      |       |
| [Tl L₃-M₄ and 1 others; 0.4968>  | Ok     | Ok      |       |
| [Tl L₂-M₁; 0.0051>               | Ok     | Ok      |       |
| [Tl L₂-M₃ and 16 others; 0.3853> | Ok     | Ok      |       |
| [Tl L₂-N₁ and 12 others; 0.0868> | Ok     | Ok      |       |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" TlBr Tl 20 --format markdown 
| Region                           | Result     | Coating | Notes                               |
|----------------------------------|------------|---------|-------------------------------------|
| [Tl O₁-O₂ and 39 others; 2.0043> | Interfered | Ok      | [Br M₅-N₃ and 13 others; 1.0008> on |
|                                  |            |         | [10,33)                             |
| [Tl M₄-N₂ and 23 others; 0.9962> | Interfered | Ok      | [Br L₃-M₁ and 15 others; 0.9991> on |
|                                  |            |         | [116,186)                           |
| [Tl M₁-O₂ and 1 others; 0.0008>  | Ok         | Ok      |                                     |
| [Tl L₃-M₁ and 1 others; 0.0243>  | Ok         | Ok      |                                     |
| [Tl L₃-M₃; 0.0003>               | Ok         | Ok      |                                     |
| [Tl L₃-M₄ and 1 others; 0.4968>  | Ok         | Ok      |                                     |
| [Tl L₂-M₁; 0.0051>               | Ok         | Ok      |                                     |
| [Tl L₂-M₃ and 16 others; 0.3853> | Interfered | Ok      | [Br K-L₂ and 1 others; 0.8708> on   |
|                                  |            |         | [1155,1226), [Br K-M₂ and 5 others; |
|                                  |            |         | 0.1292> on [1297,1372)              |
| [Tl L₂-N₁ and 12 others; 0.0868> | Interfered | Ok      | [Br K-M₂ and 5 others; 0.1292> on   |
|                                  |            |         | [1297,1372)                         |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" TlI Tl 20 --format markdown 
| Region                           | Result     | Coating | Notes                              |
|----------------------------------|------------|---------|------------------------------------|
| [Tl O₁-O₂ and 39 others; 2.0043> | Interfered | Ok      | [I N₄-O₂ and 16 others; 1.0369> on |
|                                  |            |         | [10,38), [I M₅-N₃ and 17 others;   |
|                                  |            |         | 0.9630> on [37,113)                |
| [Tl M₄-N₂ and 23 others; 0.9962> | Interfered | Ok      | [I L₃-M₁ and 24 others; 0.9991> on |
|                                  |            |         | [332,531)                          |
| [Tl M₁-O₂ and 1 others; 0.0008>  | Interfered | Ok      | [I L₃-M₁ and 24 others; 0.9991> on |
|                                  |            |         | [332,531)                          |
| [Tl L₃-M₁ and 1 others; 0.0243>  | Ok         | Ok      |                                    |
| [Tl L₃-M₃; 0.0003>               | Ok         | Ok      |                                    |
| [Tl L₃-M₄ and 1 others; 0.4968>  | Ok         | Ok      |                                    |
| [Tl L₂-M₁; 0.0051>               | Ok         | Ok      |                                    |
| [Tl L₂-M₃ and 16 others; 0.3853> | Ok         | Ok      |                                    |
| [Tl L₂-N₁ and 12 others; 0.0868> | Ok         | Ok      |                                    |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" Tl2O3 Tl 20 --format markdown 
| Region                           | Result     | Coating | Notes                            |
|----------------------------------|------------|---------|----------------------------------|
| [Tl O₁-O₂ and 39 others; 2.0043> | Interfered | Ok      | [O K-L₂ and 1 others; 1.0000> on |
|                                  |            |         | [40,64)                          |
| [Tl M₄-N₂ and 23 others; 0.9962> | Ok         | Ok      |                                  |
| [Tl M₁-O₂ and 1 others; 0.0008>  | Ok         | Ok      |                                  |
| [Tl L₃-M₁ and 1 others; 0.0243>  | Ok         | Ok      |                                  |
| [Tl L₃-M₃; 0.0003>               | Ok         | Ok      |                                  |
| [Tl L₃-M₄ and 1 others; 0.4968>  | Ok         | Ok      |                                  |
| [Tl L₂-M₁; 0.0051>               | Ok         | Ok      |                                  |
| [Tl L₂-M₃ and 16 others; 0.3853> | Ok         | Ok      |                                  |
| [Tl L₂-N₁ and 12 others; 0.0868> | Ok         | Ok      |                                  |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" Pb Pb 20 --format markdown 
| Region                           | Result | Coating | Notes |
|----------------------------------|--------|---------|-------|
| [Pb O₁-O₂ and 39 others; 2.0042> | Ok     | Ok      |       |
| [Pb M₄-N₂ and 25 others; 0.9964> | Ok     | Ok      |       |
| [Pb M₁-O₂ and 1 others; 0.0008>  | Ok     | Ok      |       |
| [Pb L₃-M₁ and 1 others; 0.0247>  | Ok     | Ok      |       |
| [Pb L₃-M₃; 0.0003>               | Ok     | Ok      |       |
| [Pb L₃-M₄ and 1 others; 0.4948>  | Ok     | Ok      |       |
| [Pb L₂-M₁; 0.0051>               | Ok     | Ok      |       |
| [Pb L₂-M₃ and 16 others; 0.3852> | Ok     | Ok      |       |
| [Pb L₂-N₁ and 12 others; 0.0883> | Ok     | Ok      |       |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" PbCO3 Pb 20 --format markdown 
| Region                           | Result     | Coating | Notes                                  |
|----------------------------------|------------|---------|----------------------------------------|
| [Pb O₁-O₂ and 39 others; 2.0042> | Interfered | Ok      | [C K-L₃ and 1 others; 1.0000> on       |
|                                  |            |         | [15,38), [O K-L₂ and 1 others; 1.0000> |
|                                  |            |         | on [40,64)                             |
| [Pb M₄-N₂ and 25 others; 0.9964> | Ok         | Ok      |                                        |
| [Pb M₁-O₂ and 1 others; 0.0008>  | Ok         | Ok      |                                        |
| [Pb L₃-M₁ and 1 others; 0.0247>  | Ok         | Ok      |                                        |
| [Pb L₃-M₃; 0.0003>               | Ok         | Ok      |                                        |
| [Pb L₃-M₄ and 1 others; 0.4948>  | Ok         | Ok      |                                        |
| [Pb L₂-M₁; 0.0051>               | Ok         | Ok      |                                        |
| [Pb L₂-M₃ and 16 others; 0.3852> | Ok         | Ok      |                                        |
| [Pb L₂-N₁ and 12 others; 0.0883> | Ok         | Ok      |                                        |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" Pb Pb 20 --format markdown 
| Region                           | Result | Coating | Notes |
|----------------------------------|--------|---------|-------|
| [Pb O₁-O₂ and 39 others; 2.0042> | Ok     | Ok      |       |
| [Pb M₄-N₂ and 25 others; 0.9964> | Ok     | Ok      |       |
| [Pb M₁-O₂ and 1 others; 0.0008>  | Ok     | Ok      |       |
| [Pb L₃-M₁ and 1 others; 0.0247>  | Ok     | Ok      |       |
| [Pb L₃-M₃; 0.0003>               | Ok     | Ok      |       |
| [Pb L₃-M₄ and 1 others; 0.4948>  | Ok     | Ok      |       |
| [Pb L₂-M₁; 0.0051>               | Ok     | Ok      |       |
| [Pb L₂-M₃ and 16 others; 0.3852> | Ok     | Ok      |       |
| [Pb L₂-N₁ and 12 others; 0.0883> | Ok     | Ok      |       |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" PbO Pb 20 --format markdown 
| Region                           | Result     | Coating | Notes                            |
|----------------------------------|------------|---------|----------------------------------|
| [Pb O₁-O₂ and 39 others; 2.0042> | Interfered | Ok      | [O K-L₂ and 1 others; 1.0000> on |
|                                  |            |         | [40,64)                          |
| [Pb M₄-N₂ and 25 others; 0.9964> | Ok         | Ok      |                                  |
| [Pb M₁-O₂ and 1 others; 0.0008>  | Ok         | Ok      |                                  |
| [Pb L₃-M₁ and 1 others; 0.0247>  | Ok         | Ok      |                                  |
| [Pb L₃-M₃; 0.0003>               | Ok         | Ok      |                                  |
| [Pb L₃-M₄ and 1 others; 0.4948>  | Ok         | Ok      |                                  |
| [Pb L₂-M₁; 0.0051>               | Ok         | Ok      |                                  |
| [Pb L₂-M₃ and 16 others; 0.3852> | Ok         | Ok      |                                  |
| [Pb L₂-N₁ and 12 others; 0.0883> | Ok         | Ok      |                                  |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" "'NIST K227'" Pb 20 --format markdown 
| Region                           | Result     | Coating | Notes                             |
|----------------------------------|------------|---------|-----------------------------------|
| [Pb O₁-O₂ and 39 others; 2.0042> | Interfered | Ok      | [O K-L₂ and 1 others; 1.0000> on  |
|                                  |            |         | [40,64), [Si L₁-L₂ and 5 others;  |
|                                  |            |         | 1.0000> on [10,21)                |
| [Pb M₄-N₂ and 25 others; 0.9964> | Interfered | Ok      | [Si K-L₂ and 3 others; 1.0000> on |
|                                  |            |         | [157,195)                         |
| [Pb M₁-O₂ and 1 others; 0.0008>  | Ok         | Ok      |                                   |
| [Pb L₃-M₁ and 1 others; 0.0247>  | Ok         | Ok      |                                   |
| [Pb L₃-M₃; 0.0003>               | Ok         | Ok      |                                   |
| [Pb L₃-M₄ and 1 others; 0.4948>  | Ok         | Ok      |                                   |
| [Pb L₂-M₁; 0.0051>               | Ok         | Ok      |                                   |
| [Pb L₂-M₃ and 16 others; 0.3852> | Ok         | Ok      |                                   |
| [Pb L₂-N₁ and 12 others; 0.0883> | Ok         | Ok      |                                   |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" "'NIST K229'" Pb 20 --format markdown 
| Region                           | Result     | Coating | Notes                             |
|----------------------------------|------------|---------|-----------------------------------|
| [Pb O₁-O₂ and 39 others; 2.0042> | Interfered | Ok      | [O K-L₂ and 1 others; 1.0000> on  |
|                                  |            |         | [40,64), [Si L₁-L₂ and 5 others;  |
|                                  |            |         | 1.0000> on [10,21)                |
| [Pb M₄-N₂ and 25 others; 0.9964> | Interfered | Ok      | [Si K-L₂ and 3 others; 1.0000> on |
|                                  |            |         | [157,195)                         |
| [Pb M₁-O₂ and 1 others; 0.0008>  | Ok         | Ok      |                                   |
| [Pb L₃-M₁ and 1 others; 0.0247>  | Ok         | Ok      |                                   |
| [Pb L₃-M₃; 0.0003>               | Ok         | Ok      |                                   |
| [Pb L₃-M₄ and 1 others; 0.4948>  | Ok         | Ok      |                                   |
| [Pb L₂-M₁; 0.0051>               | Ok         | Ok      |                                   |
| [Pb L₂-M₃ and 16 others; 0.3852> | Ok         | Ok      |                                   |
| [Pb L₂-N₁ and 12 others; 0.0883> | Ok         | Ok      |                                   |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" PbS Pb 20 --format markdown 
| Region                           | Result     | Coating | Notes                             |
|----------------------------------|------------|---------|-----------------------------------|
| [Pb O₁-O₂ and 39 others; 2.0042> | Interfered | Ok      | [S L₁-L₂ and 7 others; 1.0000> on |
|                                  |            |         | [10,31)                           |
| [Pb M₄-N₂ and 25 others; 0.9964> | Interfered | Ok      | [S K-L₂ and 3 others; 1.0000> on  |
|                                  |            |         | [213,261)                         |
| [Pb M₁-O₂ and 1 others; 0.0008>  | Ok         | Ok      |                                   |
| [Pb L₃-M₁ and 1 others; 0.0247>  | Ok         | Ok      |                                   |
| [Pb L₃-M₃; 0.0003>               | Ok         | Ok      |                                   |
| [Pb L₃-M₄ and 1 others; 0.4948>  | Ok         | Ok      |                                   |
| [Pb L₂-M₁; 0.0051>               | Ok         | Ok      |                                   |
| [Pb L₂-M₃ and 16 others; 0.3852> | Ok         | Ok      |                                   |
| [Pb L₂-N₁ and 12 others; 0.0883> | Ok         | Ok      |                                   |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" PbTe Pb 20 --format markdown 
| Region                           | Result     | Coating | Notes                               |
|----------------------------------|------------|---------|-------------------------------------|
| [Pb O₁-O₂ and 39 others; 2.0042> | Interfered | Ok      | [Te N₅-O₃ and 33 others; 1.9977> on |
|                                  |            |         | [10,107)                            |
| [Pb M₄-N₂ and 25 others; 0.9964> | Interfered | Ok      | [Te L₃-M₁ and 24 others; 0.9991> on |
|                                  |            |         | [317,506)                           |
| [Pb M₁-O₂ and 1 others; 0.0008>  | Interfered | Ok      | [Te L₃-M₁ and 24 others; 0.9991> on |
|                                  |            |         | [317,506)                           |
| [Pb L₃-M₁ and 1 others; 0.0247>  | Ok         | Ok      |                                     |
| [Pb L₃-M₃; 0.0003>               | Ok         | Ok      |                                     |
| [Pb L₃-M₄ and 1 others; 0.4948>  | Ok         | Ok      |                                     |
| [Pb L₂-M₁; 0.0051>               | Ok         | Ok      |                                     |
| [Pb L₂-M₃ and 16 others; 0.3852> | Ok         | Ok      |                                     |
| [Pb L₂-N₁ and 12 others; 0.0883> | Ok         | Ok      |                                     |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" PbSe Pb 20 --format markdown 
| Region                           | Result     | Coating | Notes                               |
|----------------------------------|------------|---------|-------------------------------------|
| [Pb O₁-O₂ and 39 others; 2.0042> | Interfered | Ok      | [Se M₄-N₂ and 13 others; 1.0009> on |
|                                  |            |         | [10,31)                             |
| [Pb M₄-N₂ and 25 others; 0.9964> | Interfered | Ok      | [Se L₃-M₁ and 15 others; 0.9991> on |
|                                  |            |         | [108,174)                           |
| [Pb M₁-O₂ and 1 others; 0.0008>  | Ok         | Ok      |                                     |
| [Pb L₃-M₁ and 1 others; 0.0247>  | Ok         | Ok      |                                     |
| [Pb L₃-M₃; 0.0003>               | Ok         | Ok      |                                     |
| [Pb L₃-M₄ and 1 others; 0.4948>  | Ok         | Ok      |                                     |
| [Pb L₂-M₁; 0.0051>               | Interfered | Ok      | [Se K-L₂ and 1 others; 0.8753> on   |
|                                  |            |         | [1086,1155)                         |
| [Pb L₂-M₃ and 16 others; 0.3852> | Interfered | Ok      | [Se K-M₂ and 5 others; 0.1247> on   |
|                                  |            |         | [1218,1289)                         |
| [Pb L₂-N₁ and 12 others; 0.0883> | Ok         | Ok      |                                     |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" PbF2 Pb 20 --format markdown 
| Region                           | Result     | Coating | Notes                            |
|----------------------------------|------------|---------|----------------------------------|
| [Pb O₁-O₂ and 39 others; 2.0042> | Interfered | Ok      | [F K-L₂ and 1 others; 1.0000> on |
|                                  |            |         | [54,80)                          |
| [Pb M₄-N₂ and 25 others; 0.9964> | Ok         | Ok      |                                  |
| [Pb M₁-O₂ and 1 others; 0.0008>  | Ok         | Ok      |                                  |
| [Pb L₃-M₁ and 1 others; 0.0247>  | Ok         | Ok      |                                  |
| [Pb L₃-M₃; 0.0003>               | Ok         | Ok      |                                  |
| [Pb L₃-M₄ and 1 others; 0.4948>  | Ok         | Ok      |                                  |
| [Pb L₂-M₁; 0.0051>               | Ok         | Ok      |                                  |
| [Pb L₂-M₃ and 16 others; 0.3852> | Ok         | Ok      |                                  |
| [Pb L₂-N₁ and 12 others; 0.0883> | Ok         | Ok      |                                  |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" Bi Bi 20 --format markdown 
| Region                           | Result | Coating | Notes |
|----------------------------------|--------|---------|-------|
| [Bi O₁-O₂ and 39 others; 2.0042> | Ok     | Ok      |       |
| [Bi M₄-N₂ and 25 others; 0.9965> | Ok     | Ok      |       |
| [Bi M₁-O₂ and 1 others; 0.0008>  | Ok     | Ok      |       |
| [Bi L₃-M₁ and 1 others; 0.0251>  | Ok     | Ok      |       |
| [Bi L₃-M₃; 0.0003>               | Ok     | Ok      |       |
| [Bi L₃-M₄ and 1 others; 0.4933>  | Ok     | Ok      |       |
| [Bi L₂-M₁; 0.0051>               | Ok     | Ok      |       |
| [Bi L₃-N₁ and 16 others; 0.3850> | Ok     | Ok      |       |
| [Bi L₂-N₁ and 14 others; 0.0895> | Ok     | Ok      |       |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" Bi2S3 Bi 20 --format markdown 
| Region                           | Result     | Coating | Notes                             |
|----------------------------------|------------|---------|-----------------------------------|
| [Bi O₁-O₂ and 39 others; 2.0042> | Interfered | Ok      | [S L₁-L₂ and 7 others; 1.0000> on |
|                                  |            |         | [10,31)                           |
| [Bi M₄-N₂ and 25 others; 0.9965> | Interfered | Ok      | [S K-L₂ and 3 others; 1.0000> on  |
|                                  |            |         | [213,261)                         |
| [Bi M₁-O₂ and 1 others; 0.0008>  | Ok         | Ok      |                                   |
| [Bi L₃-M₁ and 1 others; 0.0251>  | Ok         | Ok      |                                   |
| [Bi L₃-M₃; 0.0003>               | Ok         | Ok      |                                   |
| [Bi L₃-M₄ and 1 others; 0.4933>  | Ok         | Ok      |                                   |
| [Bi L₂-M₁; 0.0051>               | Ok         | Ok      |                                   |
| [Bi L₃-N₁ and 16 others; 0.3850> | Ok         | Ok      |                                   |
| [Bi L₂-N₁ and 14 others; 0.0895> | Ok         | Ok      |                                   |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>rem spex suitable "EDAX All" Po Po 20 --format markdown 

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>rem spex suitable "EDAX All" At At 20 --format markdown 

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>rem spex suitable "EDAX All" Rn Rn 20 --format markdown 

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>rem spex suitable "EDAX All" Fr Fr 20 --format markdown 

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>rem spex suitable "EDAX All" Ra Ra 20 --format markdown 

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>rem spex suitable "EDAX All" Ac Ac 20 --format markdown 

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" ThSiO4 Th 20 --format markdown 
| Region                           | Result     | Coating | Notes                            |
|----------------------------------|------------|---------|----------------------------------|
| [Th O₁-O₂ and 44 others; 2.0043> | Interfered | Ok      | [O K-L₂ and 1 others; 1.0000> on |
|                                  |            |         | [40,64), [Si L₁-L₂ and 5 others; |
|                                  |            |         | 1.0000> on [10,21)               |
| [Th M₄-N₂ and 24 others; 0.9953> | Ok         | Ok      |                                  |
| [Th M₂-O₁ and 6 others; 0.0030>  | Ok         | Ok      |                                  |
| [Th L₃-M₁ and 1 others; 0.0284>  | Ok         | Ok      |                                  |
| [Th L₃-M₃; 0.0004>               | Ok         | Ok      |                                  |
| [Th L₃-M₄ and 1 others; 0.4833>  | Ok         | Ok      |                                  |
| [Th L₂-M₁ and 16 others; 0.3881> | Ok         | Ok      |                                  |
| [Th L₁-M₄ and 1 others; 0.0021>  | Ok         | Ok      |                                  |
| [Th L₂-N₁ and 10 others; 0.0921> | Ok         | Ok      |                                  |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" ThO2 Th 20 --format markdown 
| Region                           | Result     | Coating | Notes                            |
|----------------------------------|------------|---------|----------------------------------|
| [Th O₁-O₂ and 44 others; 2.0043> | Interfered | Ok      | [O K-L₂ and 1 others; 1.0000> on |
|                                  |            |         | [40,64)                          |
| [Th M₄-N₂ and 24 others; 0.9953> | Ok         | Ok      |                                  |
| [Th M₂-O₁ and 6 others; 0.0030>  | Ok         | Ok      |                                  |
| [Th L₃-M₁ and 1 others; 0.0284>  | Ok         | Ok      |                                  |
| [Th L₃-M₃; 0.0004>               | Ok         | Ok      |                                  |
| [Th L₃-M₄ and 1 others; 0.4833>  | Ok         | Ok      |                                  |
| [Th L₂-M₁ and 16 others; 0.3881> | Ok         | Ok      |                                  |
| [Th L₁-M₄ and 1 others; 0.0021>  | Ok         | Ok      |                                  |
| [Th L₂-N₁ and 10 others; 0.0921> | Ok         | Ok      |                                  |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" ThF4 Th 20 --format markdown 
| Region                           | Result     | Coating | Notes                            |
|----------------------------------|------------|---------|----------------------------------|
| [Th O₁-O₂ and 44 others; 2.0043> | Interfered | Ok      | [F K-L₂ and 1 others; 1.0000> on |
|                                  |            |         | [54,80)                          |
| [Th M₄-N₂ and 24 others; 0.9953> | Ok         | Ok      |                                  |
| [Th M₂-O₁ and 6 others; 0.0030>  | Ok         | Ok      |                                  |
| [Th L₃-M₁ and 1 others; 0.0284>  | Ok         | Ok      |                                  |
| [Th L₃-M₃; 0.0004>               | Ok         | Ok      |                                  |
| [Th L₃-M₄ and 1 others; 0.4833>  | Ok         | Ok      |                                  |
| [Th L₂-M₁ and 16 others; 0.3881> | Ok         | Ok      |                                  |
| [Th L₁-M₄ and 1 others; 0.0021>  | Ok         | Ok      |                                  |
| [Th L₂-N₁ and 10 others; 0.0921> | Ok         | Ok      |                                  |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>rem spex suitable "EDAX All" Pa Pa 20 --format markdown 

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" U U 20 --format markdown 
| Region                          | Result | Coating | Notes |
|---------------------------------|--------|---------|-------|
| [U O₁-O₂ and 47 others; 2.0045> | Ok     | Ok      |       |
| [U M₄-N₂ and 34 others; 0.9987> | Ok     | Ok      |       |
| [U L₃-M₁ and 1 others; 0.0301>  | Ok     | Ok      |       |
| [U L₃-M₃; 0.0004>               | Ok     | Ok      |       |
| [U L₃-M₄ and 1 others; 0.4918>  | Ok     | Ok      |       |
| [U L₂-M₁ and 16 others; 0.3801> | Ok     | Ok      |       |
| [U L₁-M₄ and 1 others; 0.0024>  | Ok     | Ok      |       |
| [U L₂-N₁ and 1 others; 0.0022>  | Ok     | Ok      |       |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" UO2 U 20 --format markdown 
| Region                          | Result     | Coating | Notes                            |
|---------------------------------|------------|---------|----------------------------------|
| [U O₁-O₂ and 47 others; 2.0045> | Interfered | Ok      | [O K-L₂ and 1 others; 1.0000> on |
|                                 |            |         | [40,64)                          |
| [U M₄-N₂ and 34 others; 0.9987> | Ok         | Ok      |                                  |
| [U L₃-M₁ and 1 others; 0.0301>  | Ok         | Ok      |                                  |
| [U L₃-M₃; 0.0004>               | Ok         | Ok      |                                  |
| [U L₃-M₄ and 1 others; 0.4918>  | Ok         | Ok      |                                  |
| [U L₂-M₁ and 16 others; 0.3801> | Ok         | Ok      |                                  |
| [U L₁-M₄ and 1 others; 0.0024>  | Ok         | Ok      |                                  |
| [U L₂-N₁ and 1 others; 0.0022>  | Ok         | Ok      |                                  |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>spex suitable "EDAX All" U3O8 U 20 --format markdown 
| Region                          | Result     | Coating | Notes                            |
|---------------------------------|------------|---------|----------------------------------|
| [U O₁-O₂ and 47 others; 2.0045> | Interfered | Ok      | [O K-L₂ and 1 others; 1.0000> on |
|                                 |            |         | [40,64)                          |
| [U M₄-N₂ and 34 others; 0.9987> | Ok         | Ok      |                                  |
| [U L₃-M₁ and 1 others; 0.0301>  | Ok         | Ok      |                                  |
| [U L₃-M₃; 0.0004>               | Ok         | Ok      |                                  |
| [U L₃-M₄ and 1 others; 0.4918>  | Ok         | Ok      |                                  |
| [U L₂-M₁ and 16 others; 0.3801> | Ok         | Ok      |                                  |
| [U L₁-M₄ and 1 others; 0.0024>  | Ok         | Ok      |                                  |
| [U L₂-N₁ and 1 others; 0.0022>  | Ok         | Ok      |                                  |

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>rem spex suitable "EDAX All" Np Np 20 --format markdown 

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>rem spex suitable "EDAX All" Pu Pu 20 --format markdown 

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>rem spex suitable "EDAX All" Am Am 20 --format markdown 

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>rem spex suitable "EDAX All" Cm Cm 20 --format markdown 

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>rem spex suitable "EDAX All" Bk Bk 20 --format markdown 

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>rem spex suitable "EDAX All" Cf Cf 20 --format markdown 

C:\Users\nritchie\Documents\repositories\spex_quant\scripts>rem spex suitable "EDAX All" Es Es 20 --format markdown 
