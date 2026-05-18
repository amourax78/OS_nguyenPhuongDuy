18/5/2026: inc_vma_limit() from mm_vm.c, added prototype in mm64.h with the line\
/* function in mm64.c*/\
//due to the skeleton of inc_vma_limit() from mm-vm.c used the vm_map_ram\
addr_t vm_map_ram(struct pcb_t *caller, addr_t astart, addr_t aend, addr_t mapstart, int incpgnum, struct vm_rg_struct *ret_rg);
