# nullable
public class Nullable<T extends Number> { private final T value;     
  
public Nullable(T value) { this.value = value;     }
public T getValue() { return value;     }
  
public boolean isNull() { return value == null;     }
@Override public String toString() { return isNull() ? "null" : value.toString();   
  
  }
  
}
  
