---
title: "enum v7_heap_stat_what"
decl_name: "enum v7_heap_stat_what"
symbol_kind: "enum"
signature: |
  enum v7_heap_stat_what {
    V7_HEAP_STAT_HEAP_SIZE,
    V7_HEAP_STAT_HEAP_USED,
    V7_HEAP_STAT_STRING_HEAP_RESERVED,
    V7_HEAP_STAT_STRING_HEAP_USED,
    V7_HEAP_STAT_OBJ_HEAP_MAX,
    V7_HEAP_STAT_OBJ_HEAP_FREE,
    V7_HEAP_STAT_OBJ_HEAP_CELL_SIZE,
    V7_HEAP_STAT_FUNC_HEAP_MAX,
    V7_HEAP_STAT_FUNC_HEAP_FREE,
    V7_HEAP_STAT_FUNC_HEAP_CELL_SIZE,
    V7_HEAP_STAT_PROP_HEAP_MAX,
    V7_HEAP_STAT_PROP_HEAP_FREE,
    V7_HEAP_STAT_PROP_HEAP_CELL_SIZE,
    V7_HEAP_STAT_FUNC_AST_SIZE,
    V7_HEAP_STAT_BCODE_OPS_SIZE,
    V7_HEAP_STAT_BCODE_LIT_TOTAL_SIZE,
    V7_HEAP_STAT_BCODE_LIT_DESER_SIZE,
    V7_HEAP_STAT_FUNC_OWNED,
    V7_HEAP_STAT_FUNC_OWNED_MAX
  };
  
---

Heap metric id, see `v7_heap_stat()` 
