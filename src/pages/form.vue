

<template>
  <f7-page>
    <f7-navbar title="Form" back-link="Back"></f7-navbar>
    <f7-block-title>Autorepeat (Tap & hold)</f7-block-title>
    <f7-block-header>Pressing and holding one of its buttons increments or decrements the stepper’s value repeatedly. With dynamic autorepeat, the rate of change depends on how long the user continues pressing the control.</f7-block-header>
    <f7-block strong class="text-align-center">
      <f7-row>
        <f7-col>
          <f7-stepper :value="0" :min="0" :max="100" :step=".5" :autorepeat="true" :wraps="true" :manual-input-mode="true" autorepeat-dynamic="true" :decimal-point="2"></f7-stepper>
        </f7-col>
        <f7-col>
          <f7-stepper :value="0" :min="0" :max="100" :step="1" :autorepeat="true" :wraps="true" :manual-input-mode="true" autorepeat-dynamic="true" :decimal-point="2"></f7-stepper>
        </f7-col>
      </f7-row>
      <br />
      <f7-row>
        <f7-col>
          <f7-stepper :value="0" :min="0" :max="100" :step=".5" :autorepeat="true" :wraps="true" :manual-input-mode="true" autorepeat-dynamic="true" :decimal-point="2"></f7-stepper>
        </f7-col>
        <f7-col>
          <f7-stepper :value="0" :min="0" :max="100" :step="1" :autorepeat="true" :wraps="true" :manual-input-mode="true" autorepeat-dynamic="true" :decimal-point="2"></f7-stepper>
        </f7-col>
      </f7-row>
      <br />
      <f7-row>
        <f7-col>
          <f7-stepper :value="0" :min="0" :max="100" :step=".5" :autorepeat="true" :wraps="true" :manual-input-mode="true" autorepeat-dynamic="true" :decimal-point="2"></f7-stepper>
        </f7-col>
        <f7-col>
          <f7-stepper :value="0" :min="0" :max="100" :step="1" :autorepeat="true" :wraps="true" :manual-input-mode="true" autorepeat-dynamic="true" :decimal-point="2"></f7-stepper>
        </f7-col>
      </f7-row>
      <br />
      <f7-row>
        <f7-col>
          <f7-stepper :value="0" :min="0" :max="100" :step=".5" :autorepeat="true" :wraps="true" :manual-input-mode="true" autorepeat-dynamic="true" :decimal-point="2"></f7-stepper>
        </f7-col>
        <f7-col>
          <f7-stepper :value="0" :min="0" :max="100" :step="1" :autorepeat="true" :wraps="true" :manual-input-mode="true" autorepeat-dynamic="true" :decimal-point="2"></f7-stepper>
        </f7-col>
      </f7-row>
      <br />
      <f7-row>
        <f7-col>
          <f7-stepper :value="0" :min="0" :max="100" :step=".5" :autorepeat="true" :wraps="true" :manual-input-mode="true" autorepeat-dynamic="true" :decimal-point="2"></f7-stepper>
        </f7-col>
        <f7-col>
          <f7-stepper :value="0" :min="0" :max="100" :step="1" :autorepeat="true" :wraps="true" :manual-input-mode="true" autorepeat-dynamic="true" :decimal-point="2"></f7-stepper>
        </f7-col>
      </f7-row>
      <br />
      <f7-row>
        <f7-col>
          <f7-stepper :value="0" :min="0" :max="100" :step=".5" :autorepeat="true" :wraps="true" :manual-input-mode="true" autorepeat-dynamic="true" :decimal-point="2"></f7-stepper>
        </f7-col>
        <f7-col>
          <f7-stepper :value="0" :min="0" :max="100" :step="1" :autorepeat="true" :wraps="true" :manual-input-mode="true" autorepeat-dynamic="true" :decimal-point="2"></f7-stepper>
        </f7-col>
      </f7-row>
      <br />
      <f7-row>
        <f7-col>
          <f7-stepper :value="0" :min="0" :max="100" :step=".5" :autorepeat="true" :wraps="true" :manual-input-mode="true" autorepeat-dynamic="true" :decimal-point="2"></f7-stepper>
        </f7-col>
        <f7-col>
          <f7-stepper :value="0" :min="0" :max="100" :step="1" :autorepeat="true" :wraps="true" :manual-input-mode="true" autorepeat-dynamic="true" :decimal-point="2"></f7-stepper>
        </f7-col>
      </f7-row>
      <br />
      <f7-row>
        <f7-col>
          <f7-stepper :value="0" :min="0" :max="100" :step=".5" :autorepeat="true" :wraps="true" :manual-input-mode="true" autorepeat-dynamic="true" :decimal-point="2"></f7-stepper>
        </f7-col>
        <f7-col>
          <f7-stepper :value="0" :min="0" :max="100" :step=".5" :autorepeat="true" :wraps="true" :manual-input-mode="true" autorepeat-dynamic="true" :decimal-point="2"></f7-stepper>
        </f7-col>
        <f7-col>
          <f7-stepper :value="0" :min="0" :max="100" :step="1" :autorepeat="true" :wraps="true" :manual-input-mode="true" autorepeat-dynamic="true" :decimal-point="2"></f7-stepper>
        </f7-col>
      </f7-row>
      <br />
      <f7-row>
        <f7-col>
          <f7-stepper :value="0" :min="0" :max="100" :step=".5" :autorepeat="true" :wraps="true" :manual-input-mode="true" autorepeat-dynamic="true" :decimal-point="2"></f7-stepper>
        </f7-col>
        <f7-col>
          <f7-stepper :value="0" :min="0" :max="100" :step=".5" :autorepeat="true" :wraps="true" :manual-input-mode="true" autorepeat-dynamic="true" :decimal-point="2"></f7-stepper>
        </f7-col>
        <f7-col>
          <f7-stepper :value="0" :min="0" :max="100" :step="1" :autorepeat="true" :wraps="true" :manual-input-mode="true" autorepeat-dynamic="true" :decimal-point="2"></f7-stepper>
        </f7-col>
      </f7-row>
      <br />
      <f7-row>
        <f7-col>
          <f7-stepper :value="0" :min="0" :max="100" :step=".5" :autorepeat="true" :wraps="true" :manual-input-mode="true" autorepeat-dynamic="true" :decimal-point="2"></f7-stepper>
        </f7-col>
        <f7-col>
          <f7-stepper :value="0" :min="0" :max="100" :step=".5" :autorepeat="true" :wraps="true" :manual-input-mode="true" autorepeat-dynamic="true" :decimal-point="2"></f7-stepper>
        </f7-col>
        <f7-col>
          <f7-stepper :value="0" :min="0" :max="100" :step="1" :autorepeat="true" :wraps="true" :manual-input-mode="true" autorepeat-dynamic="true" :decimal-point="2"></f7-stepper>
        </f7-col>
      </f7-row>
      <br />
      <f7-row>
        <f7-col>
          <f7-stepper :value="0" :min="0" :max="100" :step=".5" :autorepeat="true" :wraps="true" :manual-input-mode="true" autorepeat-dynamic="true" :decimal-point="2"></f7-stepper>
        </f7-col>
        <f7-col>
          <f7-stepper :value="0" :min="0" :max="100" :step=".5" :autorepeat="true" :wraps="true" :manual-input-mode="true" autorepeat-dynamic="true" :decimal-point="2"></f7-stepper>
        </f7-col>
        <f7-col>
          <f7-stepper :value="0" :min="0" :max="100" :step="1" :autorepeat="true" :wraps="true" :manual-input-mode="true" autorepeat-dynamic="true" :decimal-point="2"></f7-stepper>
        </f7-col>
      </f7-row>
      <br />
      <f7-row>
        <f7-col>
          <f7-stepper :value="0" :min="0" :max="100" :step=".5" :autorepeat="true" :wraps="true" :manual-input-mode="true" autorepeat-dynamic="true" :decimal-point="2"></f7-stepper>
        </f7-col>
        <f7-col>
          <f7-stepper :value="0" :min="0" :max="100" :step=".5" :autorepeat="true" :wraps="true" :manual-input-mode="true" autorepeat-dynamic="true" :decimal-point="2"></f7-stepper>
        </f7-col>
        <f7-col>
          <f7-stepper :value="0" :min="0" :max="100" :step="1" :autorepeat="true" :wraps="true" :manual-input-mode="true" autorepeat-dynamic="true" :decimal-point="2"></f7-stepper>
        </f7-col>
      </f7-row>
      <br />
    </f7-block>
    
  
  </f7-page>
  </template>
  <script>
    export default {
      data() {
        return {
          applesCount: 0,
          orangesCount: 0,
          meetingTime: 15,
        };
      },
      computed: {
        meetingTimeComputed() {
          const self = this;
          const value = self.meetingTime;
  
          const hours = Math.floor(value / 60);
          const minutes = value - (hours * 60);
          const formatted = [];
          if (hours > 0) {
            formatted.push(hours + ' ' + (hours > 1 ? 'hours' : 'hour'));
          }
          if (minutes > 0) {
            formatted.push(minutes + ' minutes');
          }
          return formatted.join(' ');
        },
      },
      methods: {
        setApples(value) {
          this.applesCount = value;
        },
        setOranges(value) {
          this.orangesCount = value;
        },
        setMeetingTime(value) {
          this.meetingTime = value;
        },
      },
    }
  </script>