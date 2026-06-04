# Neovim Config - Cheatsheet phim tat

Leader key: `Space`

Thong tin nhanh:
- Che do: n = Normal, i = Insert, v = Visual, x = Visual-Select, o = Operator-pending, t = Terminal.
- Mot so phim tat chi co tren buffer (LSP, GitSigns) va chi hoat dong khi plugin/LSP attach.
- Neu trung phim tat, map duoc nap sau se ghi de.

## Ho tro which-key
| Mode | Key | Action |
| --- | --- | --- |
| n | `<leader>?` | Hien keymap trong buffer (which-key) |
| n | `<c-w><space>` | Che do Hydra cua so (which-key) |
| n | `<leader>W` | Ghi file |
| v | `<leader>W` | Ghi file |
| n | `<leader>fCf` | Sao chep duong dan day du |
| n | `<leader>fCn` | Sao chep ten file |
| n | `<leader>fCr` | Sao chep duong dan tuong doi |

## Dieu huong buffer
| Mode | Key | Action |
| --- | --- | --- |
| n | `<Tab>` | Buffer tiep theo |
| n | `<S-Tab>` | Buffer truoc |
| n | `<leader>bn` | Buffer tiep theo |
| n | `<leader>bp` | Buffer truoc |
| n | `<S-h>` | Buffer truoc |
| n | `<S-l>` | Buffer tiep theo |
| n | `[b` | Buffer truoc |
| n | `]b` | Buffer tiep theo |
| n | `<leader>bb` | Chuyen sang buffer truoc do |
| n | `<leader>`` | Chuyen sang buffer truoc do |
| n | `<leader>bd` | Xoa buffer (Snacks) |
| n | `<leader>bo` | Xoa cac buffer khac (Snacks) |
| n | `<leader>bl` | Dong tat ca buffer ben trai |
| n | `<leader>br` | Dong tat ca buffer ben phai |

## Quan ly cua so
| Mode | Key | Action |
| --- | --- | --- |
| n | `<C-h>` | Sang cua so ben trai |
| n | `<C-j>` | Sang cua so ben duoi |
| n | `<C-k>` | Sang cua so ben tren |
| n | `<C-l>` | Sang cua so ben phai |
| t | `<C-h>` | Sang cua so ben trai |
| t | `<C-j>` | Sang cua so ben duoi |
| t | `<C-k>` | Sang cua so ben tren |
| t | `<C-l>` | Sang cua so ben phai |
| n | `<C-S-Up>` | Tang chieu cao +5 |
| n | `<C-S-Down>` | Giam chieu cao -5 |
| n | `<C-S-Left>` | Giam chieu rong -5 |
| n | `<C-S-Right>` | Tang chieu rong +5 |
| n | `<leader>ww` | Doi cua so |
| n | `<leader>wd` | Dong cua so |
| n | `<leader>w-` | Chia cua so ben duoi |
| n | `<leader>sh` | Chia cua so ben duoi |
| n | `<leader>w|` | Chia cua so ben phai |
| n | `<leader>|` | Chia cua so ben phai |
| n | `<leader>sv` | Chia cua so ben phai |

## Tab
| Mode | Key | Action |
| --- | --- | --- |
| n | `<leader><tab>l` | Tab cuoi |
| n | `<leader><tab>o` | Dong cac tab khac |
| n | `<leader><tab>f` | Tab dau |
| n | `<leader><tab><tab>` | Tab moi |
| n | `<leader><tab>]` | Tab tiep theo |
| n | `<leader><tab>[` | Tab truoc |
| n | `<leader><tab>d` | Dong tab |

## Di chuyen va chon
| Mode | Key | Action |
| --- | --- | --- |
| n/x | `j` | Xuong (dong hien thi neu khong co count) |
| n/x | `k` | Len (dong hien thi neu khong co count) |
| n/x | `<Down>` | Xuong (dong hien thi neu khong co count) |
| n/x | `<Up>` | Len (dong hien thi neu khong co count) |
| n | `<A-j>` | Doi dong xuong |
| n | `<A-k>` | Doi dong len |
| i | `<A-j>` | Doi dong xuong |
| i | `<A-k>` | Doi dong len |
| v | `<A-j>` | Doi khoi xuong |
| v | `<A-k>` | Doi khoi len |
| v | `J` | Doi khoi xuong |
| v | `K` | Doi khoi len |
| n | `<A-Down>` | Doi dong xuong |
| n | `<A-Up>` | Doi dong len |
| i | `<A-Down>` | Doi dong xuong |
| i | `<A-Up>` | Doi dong len |
| v | `<A-Down>` | Doi khoi xuong |
| v | `<A-Up>` | Doi khoi len |
| n | `gl` | Den cuoi dong |
| n | `gh` | Den dau dong |
| n | `<A-h>` | Den dau dong |
| n | `<A-l>` | Den cuoi dong |
| n | `==` | Chon tat ca |
| n | `<A-a>` | Chon tat ca |
| n/x/o | `n` | Ket qua tim kiem tiep theo (luon tien) |
| n/x/o | `N` | Ket qua tim kiem truoc (luon lui) |

## Chinh sua
| Mode | Key | Action |
| --- | --- | --- |
| v | `<` | Thut le trai va giu Visual |
| v | `>` | Thut le phai va giu Visual |
| v | `p` | Dan ma khong ghi de clipboard |
| n | `<C-c>` | Sao chep toan bo file vao clipboard |
| i | `,` | Tao diem undo |
| i | `.` | Tao diem undo |
| i | `;` | Tao diem undo |
| i | `` ` `` | Tu dong dong backtick |
| i | `"` | Tu dong dong dau nhay kep |
| i | `(` | Tu dong dong ngoac tron |
| i | `[` | Tu dong dong ngoac vuong |
| i | `{` | Tu dong dong ngoac nhon |
| i | `<` | Tu dong dong dau ngoac nho hon |

## Tep va luu
| Mode | Key | Action |
| --- | --- | --- |
| n/i/x/s | `<C-s>` | Luu file |
| n | `<leader>fn` | Tao file moi |
| n | `<leader>qq` | Thoat tat ca |

## Tim kiem, quickfix, diagnostics
| Mode | Key | Action |
| --- | --- | --- |
| i/n | `<esc>` | Xoa highlight tim kiem |
| n | `<leader>ur` | Ve lai + xoa highlight + diff update |
| n | `<leader>xl` | Bat/tat location list |
| n | `<leader>xq` | Bat/tat quickfix list |
| n | `[q` | Quickfix truoc |
| n | `]q` | Quickfix tiep theo |
| n | `<leader>cd` | Diagnostics tai dong |
| n | `]d` | Diagnostic tiep theo |
| n | `[d` | Diagnostic truoc |
| n | `]e` | Loi tiep theo |
| n | `[e` | Loi truoc |
| n | `]w` | Canh bao tiep theo |
| n | `[w` | Canh bao truoc |

## LSP (chi khi attach)
| Mode | Key | Action |
| --- | --- | --- |
| n | `<leader>ca` | Code actions |
| n | `<leader>cr` | Doi ten symbol |
| n | `<leader>k` | Hover tai lieu |
| n | `K` | Hover tai lieu (phu) |
| n | `gd` | Den dinh nghia |

## Git (Gitsigns)
| Mode | Key | Action |
| --- | --- | --- |
| n | `]h` | Hunk tiep theo |
| n | `[h` | Hunk truoc |
| n | `]H` | Hunk cuoi |
| n | `[H` | Hunk dau |
| n/v | `<leader>ghs` | Stage hunk |
| n/v | `<leader>ghr` | Reset hunk |
| n | `<leader>ghS` | Stage buffer |
| n | `<leader>ghu` | Undo stage hunk |
| n | `<leader>ghR` | Reset buffer |
| n | `<leader>ghp` | Xem hunk inline |
| n | `<leader>ghb` | Blame dong |
| n | `<leader>ghB` | Blame ca buffer |
| n | `<leader>ghd` | Diff file |
| n | `<leader>ghD` | Diff file voi ~ |
| o/x | `ih` | Chon hunk |

## Git (vdiff.nvim)
| Mode | Key | Action |
| --- | --- | --- |
| n | `<leader>gc` | So sanh (nhap ref) |
| n | `<leader>gC` | So sanh 2 ref |
| n | `<leader>gd` | So sanh working tree voi HEAD |
| n | `<leader>gD` | So sanh staged voi HEAD |
| n | `<leader>gV` | Lich su file |
| v | `<leader>gv` | Lich su theo dong |
| n | `<leader>gx` | Dong tat ca diff view |
| n | `<leader>gm` | Merge conflicts view |
| n | `<leader>gf` | Diff file hien tai voi HEAD |
| n | `<leader>gF` | Diff file hien tai voi ref |
| n | `<leader>g2` | So sanh 2 file |

## Dinh dang (Conform)
| Mode | Key | Action |
| --- | --- | --- |
| n | `<leader>uf` | Bat/tat autoformat |
| n/v | `<leader>cn` | Thong tin Conform |
| n/v | `<leader>cf` | Format buffer |
| n/v | `<leader>cF` | Format ngon ngu nhung |

## Treesitter textobjects
| Mode | Key | Action |
| --- | --- | --- |
| x/o | `af` | Chon function outer |
| x/o | `if` | Chon function inner |
| x/o | `ac` | Chon class outer |
| x/o | `ic` | Chon class inner |
| x/o | `aa` | Chon parameter outer |
| x/o | `ia` | Chon parameter inner |
| x/o | `ad` | Chon comment outer |
| x/o | `as` | Chon statement outer |
| n/x/o | `]m` | Den bat dau function tiep theo |
| n/x/o | `[m` | Den bat dau function truoc |
| n/x/o | `]]` | Den bat dau class tiep theo |
| n/x/o | `[[` | Den bat dau class truoc |
| n/x/o | `]M` | Den ket thuc function tiep theo |
| n/x/o | `[M` | Den ket thuc function truoc |
| n/x/o | `]o` | Den bat dau vong lap tiep theo |
| n/x/o | `[o` | Den bat dau vong lap truoc |

## Snacks - picker va cong cu
| Mode | Key | Action |
| --- | --- | --- |
| n | `<leader><space>` | Tim file thong minh |
| n | `<leader>/` | Grep |
| n | `<leader>:` | Lich su lenh |
| n | `<leader>n` | Lich su thong bao |
| n | `<leader>e` | File explorer |
| n | `<leader>,` | Chon buffer (xoa bang `dd`) |
| n | `<leader>fb` | Buffer |
| n | `<leader>fc` | Tim file config |
| n | `<leader>ff` | Tim file |
| n | `<leader>fg` | Tim file trong git |
| n | `<leader>fp` | Du an |
| n | `<leader>fr` | Gan day |
| n | `<leader>gb` | Nhanh git |
| n | `<leader>gl` | Git log |
| n | `<leader>gL` | Git log (dong hien tai) |
| n | `<leader>gs` | Git status |
| n | `<leader>gS` | Git stash |
| n | `<leader>gp` | Git diff picker (hunks) |
| n | `<leader>gP` | Git diff picker (origin) |
| n | `<leader>gf` | Git log (file hien tai) |
| n | `<leader>sb` | Dong trong buffer |
| n | `<leader>sB` | Grep trong cac buffer dang mo |
| n | `<leader>sg` | Grep |
| n/x | `<leader>sw` | Grep tu/selection |
| n | `<leader>s"` | Registers |
| n | `<leader>s/` | Lich su tim kiem |
| n | `<leader>sa` | Autocmds |
| n | `<leader>sc` | Lich su lenh |
| n | `<leader>sC` | Danh sach lenh |
| n | `<leader>sd` | Diagnostics |
| n | `<leader>sD` | Diagnostics cua buffer |
| n | `<leader>sH` | Highlights |
| n | `<leader>si` | Icons |
| n | `<leader>sj` | Jumps |
| n | `<leader>sk` | Keymaps |
| n | `<leader>sl` | Location list |
| n | `<leader>sm` | Marks |
| n | `<leader>sM` | Man pages |
| n | `<leader>sq` | Quickfix list |
| n | `<leader>sR` | Resume |
| n | `<leader>su` | Lich su undo |
| n | `<leader>uC` | Colorschemes |
| n | `gd` | LSP definitions picker |
| n | `gD` | LSP declarations picker |
| n | `gR` | LSP references picker |
| n | `gI` | LSP implementations picker |
| n | `gy` | LSP type definitions picker |
| n | `<leader>ss` | LSP symbols |
| n | `<leader>sS` | LSP workspace symbols |
| n | `gai` | LSP incoming calls |
| n | `gao` | LSP outgoing calls |
| n | `<leader>fT` | Terminal (thu muc hien tai) |
| n | `<leader>ft` | Terminal (root dir) |
| n | `<c-:>` | Terminal (root dir) |
| n | `<c-/>` | Bat/tat terminal |
| n | `<leader>z` | Bat/tat Zen mode |
| n | `<leader>Z` | Bat/tat zoom |
| n | `<leader>.` | Bat/tat scratch buffer |
| n | `<leader>S` | Chon scratch buffer |
| n | `<leader>cR` | Doi ten file |
| n/v | `<leader>gB` | Mo Git browse |
| n | `<leader>gg` | Lazygit |
| n | `<leader>un` | An thong bao |
| n/t | `]]` | Tham chieu tiep theo |
| n/t | `[[` | Tham chieu truoc |
| n | `<leader>N` | Neovim news |

## Snacks - toggle giao dien
| Mode | Key | Action |
| --- | --- | --- |
| n | `<leader>uw` | Bat/tat wrap |
| n | `<leader>uL` | Bat/tat relative number |
| n | `<leader>ud` | Bat/tat diagnostics |
| n | `<leader>ul` | Bat/tat line number |
| n | `<leader>uc` | Bat/tat conceal level |
| n | `<leader>uA` | Bat/tat tabline |
| n | `<leader>uT` | Bat/tat treesitter |
| n | `<leader>ub` | Bat/tat dark background |
| n | `<leader>uD` | Bat/tat dim |
| n | `<leader>ua` | Bat/tat animation |
| n | `<leader>ug` | Bat/tat indent guides |
| n | `<leader>uS` | Bat/tat scroll |
| n | `<leader>dpp` | Bat/tat profiler |
| n | `<leader>dph` | Bat/tat profiler highlights |
| n | `<leader>wm` | Bat/tat zoom |
| n | `<leader>uZ` | Bat/tat zoom |
| n | `<leader>uz` | Bat/tat zen |

## Markdown
| Mode | Key | Action |
| --- | --- | --- |
| n | `<leader>um` | Bat/tat render markdown |
| n | `<leader>cp` | Markdown preview |

## Session
| Mode | Key | Action |
| --- | --- | --- |
| n | `<leader>qs` | Tai session cho thu muc hien tai |
| n | `<leader>ql` | Tai session gan nhat |
| n | `<leader>qS` | Chon session de tai |
| n | `<leader>qd` | Dung luu session |

## Terminal mode
| Mode | Key | Action |
| --- | --- | --- |
| t | `<esc><esc>` | Ve Normal mode |
| t | `<C-/>` | An terminal |
| t | `<c-_>` | An terminal (bo qua which-key) |

## Fold va chinh ta
| Mode | Key | Action |
| --- | --- | --- |
| n | `zv` | Dong het folds tru khi dang o fold hien tai |
| n | `zj` | Dong fold hien tai va mo fold tiep theo |
| n | `zk` | Dong fold hien tai va mo fold truoc |
| n | `<leader>tw` | Bat/tat wrap |
| n | `z0` | Sua tu duoi con tro |

## Cac buffer dac biet
Trong cac filetype nay, nhan `q` de dong cua so: help, qf, notify, lspinfo, checkhealth, va nhieu panel plugin khac (xem config).
# Neovim_Config
