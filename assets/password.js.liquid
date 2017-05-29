var extend = function(child, parent) { for (var key in parent) { if (hasProp.call(parent, key)) child[key] = parent[key]; } function ctor() { this.constructor = child; } ctor.prototype = parent.prototype; child.prototype = new ctor(); child.__super__ = parent.prototype; return child; },
  hasProp = {}.hasOwnProperty;

window.PasswordView = (function(superClass) {
  extend(PasswordView, superClass);

  function PasswordView() {
    return PasswordView.__super__.constructor.apply(this, arguments);
  }

  PasswordView.prototype.events = {
    'click [data-password-trigger]': 'togglePasswordForm'
  };

  PasswordView.prototype.initialize = function() {
    this.$newsletterForm = this.$('.newsletter-section');
    this.$newsletterToggle = this.$('[data-newsletter-toggle]');
    this.$passwordForm = this.$('[data-password-form]');
    this.$passwordToggle = this.$('[data-password-toggle]');
    this.hasErrors = this.$passwordForm.find('.has-errors').length;
    if (this.hasErrors) {
      return this.togglePasswordForm(false, true);
    }
  };

  PasswordView.prototype.togglePasswordForm = function(event, hideNewsletter) {
    if (event == null) {
      event = false;
    }
    if (hideNewsletter == null) {
      hideNewsletter = false;
    }
    if (event) {
      event.preventDefault();
    }
    if (this.$passwordForm.hasClass('visible' || hideNewsletter)) {
      this.$newsletterForm.addClass('visible').removeClass('hidden');
      this.$newsletterToggle.addClass('visible').removeClass('hidden');
      this.$passwordForm.addClass('hidden').removeClass('visible');
      return this.$passwordToggle.addClass('hidden').removeClass('visible');
    } else {
      this.$passwordForm.addClass('visible').removeClass('hidden');
      this.$passwordToggle.addClass('visible').removeClass('hidden');
      this.$newsletterForm.addClass('hidden').removeClass('visible');
      return this.$newsletterToggle.addClass('hidden').removeClass('visible');
    }
  };

  return PasswordView;

})(Backbone.View);

$(function() {
  return window.theme = new PasswordView({
    el: $(document.body)
  }).render();
});
