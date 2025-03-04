public class Main {
    public static void main(String[] args) {
        // Initialize the SDK
        JvmMetrics.initialize();
        
        // Display all JVM attributes
        JvmMetrics.showJvmAttributes();
        
        // Record sample metrics
        JvmMetrics.Metrics.recordJvmMemoryUsage(0.85);
    }
}
