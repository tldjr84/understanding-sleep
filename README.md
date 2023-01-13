# understanding-sleep
graph LR
    bedtime[Bedtime]-->bed(Go to bed)
    wakeup[Wakeup time]-->bed
    bed-->sleep(Sleep)
    sleep-->morning(Morning)
    sleep-->night(Night)
    style bedtime fill:#f9f,stroke:#333,stroke-width:4px
    style wakeup fill:#f9f,stroke:#333,stroke-width:4px
    style bed fill:#ffb347,stroke:#333,stroke-width:4px
    style sleep fill:#48c9b0,stroke:#333,stroke-width:4px
    style morning fill:#f9f,stroke:#333,stroke-width:4px
    style night fill:#f9f,stroke:#333,stroke-width:4px
