public class ActivityLifecycleSimulation {

    public void onCreate() {
        System.out.println("onCreate: Activity Created");
    }

    public void onStart() {
        System.out.println("onStart: Activity Started");
    }

    public void onResume() {
        System.out.println("onResume: Activity Resumed");
    }

    public void onPause() {
        System.out.println("onPause: Activity Paused");
    }

    public void onStop() {
        System.out.println("onStop: Activity Stopped");
    }

    public void onDestroy() {
        System.out.println("onDestroy: Activity Destroyed");
    }

    public static void main(String[] args) {
        ActivityLifecycleSimulation activity = new ActivityLifecycleSimulation();

        // Simulate opening the app
        activity.onCreate();
        activity.onStart();
        activity.onResume();

        // Simulate switching to another app
        activity.onPause();
        activity.onStop();

        // Simulate closing the app
        activity.onDestroy();
    }
}
