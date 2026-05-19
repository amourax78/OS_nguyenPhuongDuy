18/5/2026: inc_vma_limit() from mm_vm.c, added prototype in mm64.h with the line\
/* function in mm64.c*/\
//due to the skeleton of inc_vma_limit() from mm-vm.c used the vm_map_ram\
addr_t vm_map_ram(struct pcb_t *caller, addr_t astart, addr_t aend, addr_t mapstart, int incpgnum, struct vm_rg_struct *ret_rg);\
\
Function edit line: __alloc() -> vm_map_ram() from mm64.c -> vmap_page_range() from mm64.c -> alloc_pages_range() from mm64.\
\
19/5/2026
vmap_page_range() from mm64.c (updated)\
pg_getpage() from libmem.c (implemented)\
pte_get_entry() from mm64.c (implemented)\
pg_getval() from libmem.c (implemented)\

