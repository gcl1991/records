1 纯null数组是可以向上转型的

如 Integer[] x = (Integer[]) new Object[10] ,因为Object里面均为null，所以不会报错。 