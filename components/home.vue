<template>
  <div>
    <div class="uk-section uk-section-primary">
      <div class="uk-container uk-text-center">
        <h1 class="uk-margin-large-top">Call Center Application</h1>
        <p class="uk-text-lead">A call center application where callers queue up to talk to available agents.</p>
      </div>
    </div>
    <div class="uk-section uk-section-default">
      <div class="container">
        <div class="route-home uk-flex-center" uk-grid>
          <div>
            <router-link to="/agent" class="uk-button uk-button-primary uk-button-large">Join as Agent</router-link>
          </div>
          <div>
            <router-link to="/caller" class="uk-button uk-button-primary uk-button-large">Join as caller</router-link>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
